# Blood Work Analyzer

A simple project I built while learning Generative AI and LangChain.

The application takes blood work information and uses Google's Gemini model to generate an explanation of the report in a way that's easier to understand.

### What it does

- Takes blood work data as input.
- Sends the information to Gemini through LangChain.
- Generates an AI-based analysis of the report.
- Displays the response through a Streamlit interface.

### Built with

- Python
- LangChain
- Google Gemini API
- Streamlit

### Run locally

Clone the repository:

```bash
git clone https://github.com/AaryanM3hta/blood-report-analyzer
cd blood-report-analyzer
```

Install the dependencies and configure your Gemini API key in a `.env` file.

Run the application:

```bash
streamlit run streamlit_app/app.py
```

### Note

This is a learning project and is intended for educational purposes only. The generated analysis should not be treated as medical advice or a substitute for a doctor's opinion.
