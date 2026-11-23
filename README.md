# Job Description Simplifier

## Project Overview
Job Description Simplifier is an LLM-based application that converts lengthy and complex job descriptions into simple, structured information using Google Gemini AI.

Users can paste a job description and receive important details in an organized table.

## Problem Statement
Job descriptions often contain lengthy and confusing information. Job seekers may find it difficult to identify the essential skills, experience, salary and responsibilities required for a position.

This project simplifies the process by automatically extracting relevant information using a Large Language Model.

## Features
- Extracts job role and required skills.
- Identifies required experience.
- Extracts salary information.
- Summarizes job responsibilities.
- Identifies educational qualifications.
- Displays missing information as "Not mentioned".
- Presents results in a structured table.
- Provides a Clear button to reset the input.

## Technology Stack
- Python
- Streamlit
- Google Gemini AI
- Google GenAI SDK
- Pandas
- JSON
- Python-dotenv

## Installation and Setup

1. Clone the repository:

   git clone https://github.com/AnanyaSaxena-15/JobDescriptionSimplifier.git

2. Open the project folder:

   cd JobDescriptionSimplifier

3. Create a virtual environment:

   python -m venv venv

4. Activate the environment:

   Windows PowerShell:
   .\venv\Scripts\Activate.ps1

5. Install dependencies:

   pip install -r requirements.txt

6. Create a `.env` file in the project folder and add:

   GEMINI_API_KEY=your_api_key_here

7. Run the application:

   streamlit run app.py

## How It Works
1. User pastes a job description.
2. The application sends the text to Gemini AI.
3. Gemini extracts information in a predefined JSON structure.
4. Python processes the JSON response.
5. Pandas organizes the extracted information into a table.
6. Streamlit displays the simplified job description.

## Project Structure

JobDescriptionSimplifier/
- app.py
- check_models.py
- requirements.txt
- .gitignore
- .env (not uploaded)

## Developed By
Ananya Saxena
