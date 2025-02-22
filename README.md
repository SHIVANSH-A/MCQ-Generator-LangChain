# 📑MCQ Generator

## 📌 Overview
MCQ Generator is a web-based application that allows users to generate multiple-choice questions (MCQs) from uploaded documents (PDF, TXT, DOCX). It uses Flask for the backend and a sleek frontend with HTML, CSS, and JavaScript.
You can also download generated mcqs as pdf.

## 🚀 Features
- Upload a document (PDF, TXT, DOCX) to extract text
- Specify the number of MCQs to generate
- Responsive UI with a clean and modern design
- Flask-powered backend for processing text and generating MCQs

## 🛠️ Technologies Used
- **Frontend:** HTML, CSS (Black, White & Blue theme)
- **Backend:** Flask (Python)
- **Styling:** Custom CSS with flexbox and animations

## 📂 Project Structure
```
MCQ-LANGCHAIN/
│-- app.py                # Main Flask application
│-- templates/
│   │-- index.html        # Frontend UI
│-- requirements.txt      # Python dependencies
│-- README.md             # Project documentation
```

## 🏗️ Setup Instructions
### Prerequisites
Make sure you have Python installed (preferably Python 3.10+).

### 1️⃣ Clone the Repository
```sh
git clone https://github.com/your-username/mcq-generator.git
cd mcq-generator
```

### 2️⃣ Create a Virtual Environment (Recommended)
```sh
python -m venv .venv
source .venv/bin/activate  # MacOS/Linux
.venv\Scripts\activate     # Windows
```

### 3️⃣ Install Dependencies
```sh
pip install -r requirements.txt
```

### 4️⃣ Run the Application
```sh
python app.py
```

The app should now be running at `http://127.0.0.1:5000/`

## 🔧 Usage
1. Open the web app in your browser.
2. Upload a document (PDF, TXT, or DOCX).
3. Enter the number of MCQs you want.
4. Click **Generate MCQs**.
5. Download and review the generated questions!

## 🎨 UI Preview
The UI follows a clean and minimalistic design with a **black, white, and blue color scheme**.

---
Happy Coding! 🎉

