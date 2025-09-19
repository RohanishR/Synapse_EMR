# # Synapse EMR

A prototype Electronic Medical Record system designed to assist healthcare professionals by using AI to summarize patient data and predict health risks. This project was built for the [NeuralDAO Hackathon].

Our goal is to turn cluttered medical data into clear, actionable insights, helping to reduce physician burnout and improve the speed and quality of patient care.

---
Here is our video link:Synapse EMR
https://youtu.be/SIIvIC4NGfc

----
### ## 🎯 Core Features

We focused on features that provide immediate value to a busy clinician:

* **AI-Generated Summaries**
    Instantly condenses lengthy clinical notes and patient histories into key bullet points, allowing doctors to get up to speed in seconds, not minutes.

* **Predictive Readmission Risk**
    Uses patient data to calculate a risk score for hospital readmission. This helps care teams identify high-risk individuals who may need proactive follow-up care.

* **Clean, Uncluttered Interface**
    Designed with a focus on simplicity and ease of use, ensuring that important information is front and center without distracting elements.

---

### ## 💡 Technology Choices

The technologies for this project were chosen for their power and speed of development:

* **Python (Flask):** The backend is built with Python for its robust data processing libraries and the simplicity of the Flask web framework, allowing for rapid API development.
* **React:** The frontend is a modern single-page application built with React, chosen for its ability to create fast, interactive, and component-based user interfaces.
* **Google Gemini API:** We leveraged Google's powerful generative models for our core AI features, specifically for summarizing complex medical text and powering our intelligent search.

---

### ## 🚀 How to Run

#### **Prerequisites**
* Python 3.8+
* Node.js & npm
* An active **Google Gemini API Key**. You can get one from Google AI Studio.

#### **Installation & Setup**

1.  **Clone this repository:**

2.  **Install all dependencies:**
    ```bash
    # Install backend packages
    pip install -r requirements.txt

    # Install frontend packages (from the /frontend folder)
    cd frontend
    npm install
    ```

3.  **Configure your API Key:**
    * In the main project folder, rename the `.env.example` file to `.env`.
    * Open the `.env` file and add your **Google Gemini API Key**. The variable name should be `GEMINI_API_KEY`.
        ```
        GEMINI_API_KEY="your_gemini_api_key_here"
        ```

4.  **Start the application servers:**
    ```bash
    # Run the Flask backend (from the root folder)
    python app.py

    # Run the React frontend (from the /frontend folder in a new terminal)
    npm run dev
    ```

5.  Open your browser and navigate to `http://localhost:3000` (or your configured port).

---

**Team:** Created by [Rohanish Raman] and [Dhyan Patel].
