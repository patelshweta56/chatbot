# 🤖 Q&A Chatbot with Ollama (Local LLM)

A simple and powerful **Q&A Chatbot** built using **Streamlit**, **LangChain**, and **Ollama**.  
This application runs **locally** using open-source LLMs like **Mistral**, so no paid API is required.

---

## 🚀 Features

- 💬 Interactive chatbot UI using Streamlit  
- 🧠 Powered by local LLMs via Ollama  
- 🔗 LangChain integration for prompt handling  
- ⚡ Runs completely offline  
- 🎛️ Adjustable parameters (temperature, max tokens)  

---

## 🛠️ Tech Stack

- Python 3.10+
- Streamlit
- LangChain
- Ollama
- python-dotenv

---

## 📂 Project Structure

```
Q&A-Chatbot/
│── app.py
│── requirements.txt
│── .env
│── README.md
```

---

## ⚙️ Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
```

---

### 2. Create Virtual Environment (Conda Recommended)

```bash
conda create -n chatbot_env python=3.10
conda activate chatbot_env
```

---

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

---

### 4. Install & Run Ollama

Download Ollama: https://ollama.com/

Start Ollama:
```bash
ollama serve
```

Pull the model:
```bash
ollama pull mistral
```

---

### 5. Set Environment Variables

Create a `.env` file in the root directory:

```env
LANGCHAIN_API_KEY=your_langsmith_api_key
LANGCHAIN_TRACING_V2=true
LANGCHAIN_PROJECT=Q&A Chatbot
```

---

### 6. Run the Application

```bash
streamlit run app.py
```

---

## 🧪 Usage

1. Open the app in your browser  
2. Enter your question  
3. Get instant responses from the chatbot  

---

## ⚠️ Important Notes

- Ensure Ollama is running before starting the app  
- Make sure the model (`mistral`) is downloaded  

---

## 🔐 Security

- Store API keys in `.env`  
- Add `.env` to `.gitignore`  
- Regenerate keys if accidentally exposed  

---

## 🌟 Future Improvements

- Add chat memory  
- Support multiple models (Llama3, Phi3, etc.)  
- Improve UI/UX  
- Deploy to cloud  

---


## 📜 License

This project is licensed under the MIT License.

---

## 👩‍💻 Author

Shweta Patel

