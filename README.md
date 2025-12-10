<img width="1280" height="731" alt="image" src="https://github.com/user-attachments/assets/9bae84b1-aa4c-4455-b27a-db69d1f81573" />


# **🩺 AI Doctor Chatbot**

An intelligent medical query assistant built using **Google Gemini 1.5 Flash**, designed to provide symptom-based guidance, general medical insights, and wellness recommendations. This project demonstrates the practical use of Large Language Models (LLMs) in conversational healthcare applications.

---

## **📌 Project Overview**

The **AI Doctor Chatbot** is a text-based conversational system that allows users to ask medical questions in natural language and receive contextual, informative responses.
It can assist with:

* Symptom interpretation
* General medical advice
* Preventive care suggestions
* Health & wellness recommendations

> **Note:** The chatbot provides *general guidance only* and does **not** replace professional medical consultation.

---

## **✨ Features**

* **LLM-Powered Responses**
  Uses Google Gemini 1.5 Flash for accurate, context-aware medical guidance.

* **Medical Query Handling**
  Supports queries related to symptoms, conditions, medicines, diet, and lifestyle.

* **Simple & Lightweight**
  Straightforward Python script with minimal dependencies.

* **Terminal-Based Chat Interface**
  Supports multi-turn conversation flow until the user types `exit`.

* **Secure API Integration**
  Uses environment variables to protect the Gemini API key.

---

## **🧠 Tech Stack**

| Component            | Technology                         |
| -------------------- | ---------------------------------- |
| Language Model       | Google Gemini 1.5 Flash            |
| Programming Language | Python                             |
| Core Libraries       | google-generativeai, python-dotenv |
| Interface            | CLI (Command Line Chat Loop)       |

---

## **📁 Project Structure**

```
AI-Doctor-Chatbot/
│
├── healthchatbot.py      # Main chatbot code
├── .env                  # Stores API key (user-created)
└── README.md             # Project documentation
```

---

## **⚙️ Installation & Setup**

### **1. Clone the Repository**

```bash
git clone https://github.com/tejalubale26/AI-Doctor-Chatbot.git
cd AI-Doctor-Chatbot
```

### **2. Install Required Libraries**

```bash
pip install -q -U google-generativeai python-dotenv
```

### **3. Add Your Gemini API Key**

Create a `.env` file in the project folder:

```
GEMINI_API_KEY=your_api_key_here
```

### **4. Run the Chatbot**

```bash
python healthchatbot.py
```

---

## **🖥️ How to Use**

Once the script is running:

1. Enter any medical or symptom-related question.
2. The chatbot responds in real time with LLM-powered guidance.
3. Type **`exit`** to end the session.

**Example:**

```
Enter your medical question (or type 'exit'): I have a headache and fatigue. What should I do?
```

---

## **📌 Sample Interaction**

**User:**
I have a sore throat and mild fever. What should I do?

**AI Doctor:**
A sore throat with mild fever may indicate a viral infection, dehydration, or seasonal illness.
Try warm fluids, rest, and salt-water gargles.
If symptoms persist beyond 48–72 hours or worsen, seek professional medical attention.

---

## **⚠️ Important Disclaimer**

This chatbot is intended solely for **general educational and informational purposes**.
It:

* Does **not** provide medical diagnosis
* Does **not** replace professional healthcare
* Should **not** be used for emergencies

Always consult a registered medical professional for health concerns.

---

## **🚀 Future Improvements**

Planned enhancements:

* Gradio or Streamlit UI
* Symptom-to-disease mapping engine
* Medical knowledge graph integration
* Chat history memory
* Voice-based interaction

---

## **🤝 Contributing**

Contributions are welcome!
Feel free to:

* Open an Issue
* Submit a Pull Request
* Suggest new features or improvements

---

## **⭐ Support**

If you found this project helpful, consider giving it a **star** on GitHub!

---

## **📬 Contact**

**Developer:** Tejal Ubale
**GitHub:** [https://github.com/tejalubale26](https://github.com/tejalubale26)
**LinkedIn:** [https://www.linkedin.com/in/tejal-ubale-0aa8b3248/](https://www.linkedin.com/in/tejal-ubale-0aa8b3248/)

---

