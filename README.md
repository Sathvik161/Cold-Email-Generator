 📧 Cold Mail Generator

A cold email generator for service-based companies using Groq, LangChain, and Streamlit. This tool allows users to input the URL of a company’s careers page, extracts relevant job listings, and generates personalized cold emails. Each email includes portfolio links sourced from a vector database to tailor the message to specific job requirements.

### Table of Contents
1. [Features](#features)
2. [Architecture Diagram](#architecture-diagram)
3. [Setup](#setup)
4. [Usage](#usage)
5. [Requirements](#requirements)

---

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

---

### Usage

1. **Open the App**: After running the command above, a new window will open in your default browser, displaying the Cold Mail Generator interface.
   
2. **Input a Careers Page URL**: Paste the URL of the target company’s careers page and click **Submit**.

3. **Generated Output**: 
   - The app will display the extracted job listings.
   - For each job, it generates a personalized cold email with relevant portfolio links.

---

### Requirements

- **Python**: Ensure Python 3.7+ is installed.
- **Environment Variables**: Set up your `.env` file with `GROQ_API_KEY`.
- **Dependencies**: Install all dependencies from `requirements.txt`.


 
 
