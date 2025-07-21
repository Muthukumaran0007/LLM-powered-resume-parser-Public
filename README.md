# 🧠 Resume Parser with OpenAI & LangChain

This project is a high-performance resume parsing pipeline built using OpenAI GPT models and LangChain's Pydantic extraction chains. It reads resumes in `.pdf` or `.docx` formats and extracts structured data for candidate profiles, including basic details, education, skills, and work experience.

## 📦 Features

- 🔍 Extracts:
  - Name, bio, location, phone, job title
  - Work experience (company, role, dates, description)
  - Education details (qualification, institute, country, year)
  - Skills, certifications, awards, hobbies

- ⚡ Fast multi-threaded execution
- 🔁 Fallback prompts for timeout recovery
- ✅ Schema enforcement with Pydantic
- 📄 Supports `.pdf` and `.docx` formats

## 🛠️ Requirements

- Python 3.9+
- OpenAI API Key
- Pip packages from `requirements.txt`

Install dependencies:

bash
pip install -r requirements.txt

🚀 Usage
Run the script from the terminal:

python main.py <resume_file_path> --model_name <openai_model_name>

⚙️ Extensibility
You can extend this framework to:
- Support .txt or .html resume formats
- Add web server interface using Flask/FastAPI
- Integrate visualization dashboards (Streamlit/Gradio)
- Store results in a database (Postgres/Mongo)
  
📋 License
This project is open for customization. License it as needed (MIT, Apache, etc.).
