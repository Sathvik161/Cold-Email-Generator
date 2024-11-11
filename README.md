

---

#  Cold Mail Generator

A cold email generator for service-based companies using Groq, LangChain, and Streamlit. This tool allows users to input the URL of a company’s careers page, extracts relevant job listings, and generates personalized cold emails. Each email includes portfolio links sourced from a vector database to tailor the message to specific job requirements.

### Features

- Extract job postings directly from a company’s careers page
- Generate personalized cold emails with job-specific portfolio links
- Leverage Groq’s Llama-based language models with LangChain
- Interactive Streamlit UI for easy URL input and email generation

---

### Setup

1. **Get a Groq API Key**:
   - Sign up and generate an API key from [Groq's Console](https://console.groq.com/keys).
   - In the `app/.env` file, set the `GROQ_API_KEY` environment variable:
     ```plaintext
     GROQ_API_KEY=your_groq_api_key_here
     ```

2. **Install Dependencies**:
   - Run the following command in your terminal to install required packages:
     ```shell
     pip install -r requirements.txt
     ```

3. **Run the Streamlit Application**:
   - Launch the app with Streamlit:
     ```shell
     streamlit run app/main.py
     ```


