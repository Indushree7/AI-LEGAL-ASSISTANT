# AI-LEGAL-ASSISTANT
---

# 🧠 AI Legal Assistant (India) 🇮🇳

An intelligent, multi-agent powered legal assistant capable of analyzing legal queries, identifying relevant **Indian Penal Code (IPC)** sections, and drafting **preliminary legal complaints**.

Built using the **CrewAI multi-agent framework**, **Flask**, and **real-time response streaming** for a dynamic, chatbot-like user experience.

---

## 🚀 Features

* 🤖 **Multi-Agent Legal Reasoning**
  Utilizes CrewAI’s multi-agent framework to break down legal queries, perform context analysis, and retrieve relevant IPC sections intelligently.

* 📜 **Automated Legal Drafting**
  Automatically generates well-structured preliminary legal complaints based on user queries and identified IPC sections.

* 🌐 **Interactive Web Interface**
  A clean, user-friendly Flask web application serves as the front-end for users to interact with the legal assistant seamlessly.

* ⚡ **Real-Time Response Streaming**
  Delivers streaming chatbot responses, making the interaction feel fast, fluid, and conversational.

---

## 🏗️ System Architecture

```
+---------------------+
|  User Interface     |  ← Flask (Frontend)
+---------------------+
            ↓
+---------------------+
|  Flask Backend API  |
+---------------------+
            ↓
+------------------------------+
|  CrewAI Multi-Agent System   |
| - Query Understanding Agent  |
| - Legal Knowledge Agent      |
| - Drafting Agent             |
+------------------------------+
            ↓
+--------------------------+
|  IPC Knowledge Base /    |
|  Legal Database          |
+--------------------------+
```

---

## 🧰 Tech Stack

| Component             | Technology                                      |
| --------------------- | ----------------------------------------------- |
| Multi-Agent Framework | [CrewAI](https://github.com/joaomdmoura/crewai) |
| Backend               | Python, Flask                                   |
| Frontend              | HTML, CSS, JS (Jinja Templates)                 |
| Streaming             | Flask Streaming API / SSE                       |
| Legal Knowledge       | Custom IPC Section Retrieval                    |

---

## 📦 Installation

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/ai-legal-assistant.git
cd ai-legal-assistant
```

### 2. Create and Activate Virtual Environment

```bash
python3 -m venv venv
source venv/bin/activate  # For Linux/Mac
# OR
venv\Scripts\activate     # For Windows
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Set Environment Variables

Create a `.env` file in the project root:

```
OPENAI_API_KEY=your_api_key_here
FLASK_ENV=development
```

(Include other keys or configurations if your CrewAI setup requires them.)

### 5. Run the Application

```bash
flask run
```

Visit: [http://localhost:5000](http://localhost:5000)

---

## 🧪 Example Usage

**User Query:**

> “My neighbor has been threatening me repeatedly. What can I do legally?”

**AI Legal Assistant Response:**

* Identifies relevant IPC sections (e.g., **Section 503** – Criminal Intimidation).
* Generates a preliminary complaint draft addressing the legal context.
* Streams response live to the web interface for a chatbot-like experience.

---

## 📝 Roadmap / Future Enhancements

* [ ] Integrate more legal acts beyond IPC (e.g., CrPC, IT Act).
* [ ] Add support for multiple languages (e.g., Hindi, Kannada).
* [ ] Expand to handle legal document uploads and extraction.
* [ ] Implement user authentication and case history management.
* [ ] Deploy on cloud (e.g., AWS / Render / Vercel).

---

## 🛡️ Disclaimer

> ⚠️ **This tool is intended for informational and educational purposes only.**
> It does not provide legal advice. For official legal consultation, please contact a licensed lawyer.


---

## 🌟 Acknowledgements

* [CrewAI](https://github.com/joaomdmoura/crewai) for the multi-agent framework.
* OpenAI API for language understanding and generation.
* Indian Penal Code resources for legal reference.

---

