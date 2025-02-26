# GenAI Projects

## 📌 Introduction
Welcome to the **GenAI Projects** repository! This repository contains various projects exploring the capabilities of Generative AI, including natural language processing, automated content generation, and AI-powered applications.

This project specifically focuses on a **Cold Email Generator** using **LLaMA 3.3** with **Groq, LangChain, and ChromaDB** to generate high-quality, AI-powered cold emails.

## 🚀 Features
- **Cold Email Generation**: Uses LLaMA 3.3 to generate personalized cold emails.
- **Groq API Integration**: Leverages Groq for efficient AI computations.
- **LangChain Integration**: Chains together AI models and prompts for improved responses.
- **ChromaDB for Vector Search**: Stores and retrieves relevant email contexts.
- **Modular Codebase**: Well-structured components for scalability and maintainability.

## 📂 Project Structure
```
genai-projects/
│── email generator/
│   ├── app/
|       ├──main.py             # Entry point for email generation
│       ├── chain.py            # Handles LLM processing and email prompts
│       ├── portfolio.py        # Reads data from my_portfolio.csv
│       ├── utils.py            # JSON parser (converts str -> JSON)
|       │── requirements.txt        # List of dependencies
│       ├── resource/
│           ├── my_portfolio.csv    # Portfolio details for personalization

│── README.md               # Project documentation
```

## 🛠️ Installation
To set up and run the project, follow these steps:

1. **Clone the repository**:
   ```sh
   git clone https://github.com/Thabeswar/genai-projects.git
   cd genai-projects
   ```

2. **Create a virtual environment**:
   ```sh
   python -m venv venv
   source venv/bin/activate  # On macOS/Linux
   venv\Scripts\activate     # On Windows
   ```

3. **Install dependencies**:
   ```sh
   pip install -r requirements.txt
   ```

## 📝 Usage
Run the AI-powered cold email generator:
```sh
streamlit run main.py --input "give a company's job link"
```


## 📜 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 📧 Contact
For any inquiries, open an issue in the [GitHub Issues](https://github.com/Thabeswar/genai-projects/issues) section.

