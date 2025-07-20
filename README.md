# InsightForge

**InsightForge** is an offline, AI-powered slide deck generator designed for data analysts, marketers, and operators who need to turn tabular data into visual presentations — fast.

> Think: "I just woke up and my data presentation is in 20 minutes."

---

## ✨ Features

- 🧠 Offline AI assistant (LLM via `llama-cpp-python`)
- 📊 Tabular data → natural language insights + charts
- 📈 Built-in chart and image generation
- 🎛️ Template-based workflows: A/B tests, pitch decks, QBRs
- 🎨 Drag-and-drop slide builder (WIP)
- 🤖 Context-aware chatbot available on every screen

---

## 🔧 Stack

| Layer         | Tech                          |
|---------------|-------------------------------|
| UI            | HTML/CSS via `pywebview`      |
| Backend       | Flask (REST bridge)           |
| AI Text       | `llama-cpp-python`, Mixtral   |
| Embeddings    | `sentence-transformers`       |
| Charts        | `matplotlib`, (future: D3.js) |
| Images (TBD)  | Local image generation model  |

---

## 🚀 Getting Started

1. Clone the repo:
   ```bash
   git clone https://github.com/yourname/insightforge.git
   cd insightforge
   ```

2. Create virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # or venv\Scripts\activate on Windows
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Launch app:
   ```bash
   python app.py
   ```

---

## 📁 Structure

```
InsightForge/
├── app.py
├── frontend/
│   └── screen_one.html
├── backend/
│   └── server.py (coming soon)
├── models/         # Local AI/ML models
├── static/         # Charts, assets, SVGs
└── README.md
```

---

## 💡 Vision

InsightForge aims to make natural language a **first-class UI** for data. Forget fiddling with Excel charts — just tell the assistant what you want and build presentations in seconds.

---

## 📜 License

Dual: MPL-2.0 for code, commercial for compiled binaries.

---

## 🧪 Status

**Alpha** – actively under construction.
