# 🧠 AI Tweet Generator Agent (LangGraph + Groq)

An **agentic AI system** that generates, evaluates, and optimizes tweets using a multi-step workflow built with **LangGraph** and **Groq LLMs**.

---

## 🚀 Features

* 🧵 Generates viral-style tweets
* 🧠 Evaluates tweets using AI critic
* 🔁 Iteratively improves tweets
* 📊 Maintains history (stateful workflow)
* ⚡ Built using LangGraph (agentic execution)

---

## 🏗️ Architecture

This project follows an **Agentic AI Loop**:

```
Generate → Evaluate → Optimize → Repeat
```

### Nodes:

* `generate` → creates tweet
* `evaluate` → judges tweet quality
* `optimize` → improves tweet
* Conditional routing decides next step

---

## 🧩 Tech Stack

* **LangGraph** → Workflow orchestration
* **LangChain Core** → Message handling
* **Groq API** → Fast LLM inference
* **Pydantic** → Structured outputs

---

## 📂 Project Structure

```
.
├── main.py
├── requirements.txt
├── README.md
├── .env (not pushed)
└── .gitignore
```

---

## ⚙️ Setup Instructions

### 1. Clone repo

```bash
git clone https://github.com/your-username/tweet-agent.git
cd tweet-agent
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Add API Key

Create `.env` file:

```
GROQ_API_KEY=your_api_key_here
```

---

## ▶️ Run the Project

```bash
python main.py
```

---

## 🧠 How It Works

### 1. Tweet Generation

* Uses creative LLM prompt
* Produces humorous tweet

### 2. Evaluation

* Checks:

  * Humor
  * Originality
  * Virality
  * Format

### 3. Optimization Loop

* If not approved → rewritten
* Loop continues until:

  * Approved ✅
  * Max iterations reached

---

## 🔁 Example Flow

```
Topic: World War

Iteration 1 → Weak tweet ❌
Iteration 2 → Improved 😐
Iteration 3 → Viral tweet ✅
```

---

## ⚠️ Important Notes

* Do NOT push `.env` file (contains API keys)
* Add `.env` to `.gitignore`

---

## 📌 Future Improvements

* Add Streamlit UI
* Deploy on HuggingFace / Vercel
* Add tweet scoring metrics
* Store results in database

---

## 👨‍💻 Author

Jatin

---

## 📜 License

MIT License (recommended)

