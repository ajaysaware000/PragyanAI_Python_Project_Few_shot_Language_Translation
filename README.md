# Few-Shot Language Translation: English to Kannada using Groq

A Streamlit-based language translation application that converts English text into Kannada using **Few-Shot Prompting** and the **Groq LLM API**.

---

# 🌐 Streamlit Application Link

You can access the English to Kannada Translator using the link below:

> Note: Replace `YOUR_STREAMLIT_APP_LINK` with your actual deployed Streamlit application URL.

Example:

[Click Here to Open the Streamlit App](https://pragyanaipythonprojectfewshotlanguagetranslation-uojr8tatzbcph.streamlit.app/)

---

# 📌 Project Overview

This project translates English sentences into Kannada using a Large Language Model (LLM) through the Groq API.  
It uses **Few-Shot Prompting**, where a few English-to-Kannada translation examples are provided to the model before translating the user’s input.

Few-shot examples help the LLM understand the translation pattern and generate more accurate and natural Kannada output.

---

# 🚀 Features

- Translate English text into Kannada
- Uses Few-Shot Prompting for better translation accuracy
- Built using Streamlit web interface
- Uses Groq Client and Groq API for LLM communication
- Simple and user-friendly design
- Fast translation using Groq LLM
- Easy to extend for other regional languages

---

# 🛠️ Tools and Technologies Used

| Tool / Technology | Purpose |
|---|---|
| **Streamlit** | Used to build the web application |
| **Groq** | AI platform used to access LLM models |
| **Groq Client** | Used to connect Python application with Groq API |
| **Groq API** | Used to send prompts and receive translations |
| **Groq API Key** | Used for authentication |
| **Few-Shot Prompting** | Used to provide translation examples to the model |
| **Chat Completions API** | Used to communicate with the LLM |
| **Python** | Main programming language |
| **Environment Variables** | Used to store the Groq API key securely |

---

# ⚙️ Installation

## 1. Clone the Repository

```bash
git clone [https://github.com/your-username/few-shot-english-kannada-translator.git](https://github.com/your-username/few-shot-english-kannada-translator.git)
cd few-shot-english-kannada-translator
```

## 2. Install Required Libraries

```bash
pip install streamlit groq python-dotenv
```

---

# 🔐 Groq API Key Setup

Create a `.env` file in the project folder and add your Groq API key:

```env
GROQ_API_KEY=your_groq_api_key
```

Get your API key from the Groq Console.

---

# 🧠 Few-Shot Prompting

Few-Shot Prompting provides a few solved examples before the actual translation task.

Example prompt:

```text
Translate English to Kannada.

English: Hello
Kannada: ನಮಸ್ಕಾರ

English: How are you?
Kannada: ನೀವು ಹೇಗಿದ್ದೀರಾ?

English: Good morning
Kannada: ಶುಭೋದಯ

English: I am learning Python.
Kannada:
```

The model learns the translation pattern from the examples and translates the final English sentence into Kannada.

---

# 🖥️ Application Workflow

```text
User English Input
        ↓
Few-Shot Prompt Creation
        ↓
Groq Client
        ↓
Groq LLM API
        ↓
Kannada Translation
        ↓
Streamlit Output Display
```

---

# ▶️ Run the Project

After installing the requirements and setting the API key, run:

```bash
streamlit run app.py
```

Then open the generated local URL in your browser:

```text
http://localhost:8501
```

---

# 📊 Example

**English Input:**

```text
I am learning Python.
```

**Kannada Output:**

```text
ನಾನು ಪೈಥಾನ್ ಕಲಿಯುತ್ತಿದ್ದೇನೆ.
```

---

# ✅ Advantages

- Provides quick English to Kannada translation
- Few-shot prompting improves translation accuracy
- Simple and interactive Streamlit interface
- Uses fast Groq LLM responses
- Helpful for users who do not know Kannada
- Reduces manual translation effort
- Can be extended to other languages

---

# 🔮 Future Scope

- Add Kannada to English translation
- Support more regional languages
- Add voice input and speech output
- Allow document translation
- Save translation history
- Improve accuracy using more examples
- Deploy on Streamlit Community Cloud
- Add copy-to-clipboard feature

---

# 🧪 Testing

The application was tested using different English sentences such as greetings, questions, and daily-use sentences.

Test cases included:

- Simple sentence translation
- Question translation
- Greeting translation
- Few-shot prompt validation
- Groq API response checking
- Streamlit interface testing

---

# 📌 Conclusion

This project successfully demonstrates English to Kannada translation using Few-Shot Prompting and the Groq LLM API.  
The use of translation examples helps the model generate more accurate and natural Kannada output.

---

# 👨‍💻 Developed By

**Ajay Saware**  

---
