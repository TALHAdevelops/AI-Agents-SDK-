# 🧠 AI Writer Agent with Gemini API + Streamlit

This project is a simple yet powerful **AI content generation tool** built with **Streamlit** and powered by **Google's Gemini 2.0 Flash** model via its **OpenAI-compatible API**.

The app uses a custom AI agent to generate high-quality content — essays, articles, and more — based on your input prompt.

---

## ✨ Features

- 🧠 Custom AI agent with writing expertise
- 🔌 Gemini 2.0 Flash via OpenAI-compatible API
- ⚡ Fully async architecture for performance
- 🖥️ Minimal Streamlit interface for interaction
- 📄 Clean and extensible project structure

---

## 📸 Preview

<!-- Add a screenshot or screen recording if available -->
> Coming Soon...

---

## 🧰 Tech Stack

| Layer        | Tool / Library                         |
|--------------|----------------------------------------|
| UI           | [Streamlit](https://streamlit.io)      |
| AI API       | [Gemini via OpenAI-compatible API](https://ai.google.dev/gemini-api/docs/openai) |
| Language     | Python 3.11+                           |
| Environment  | `python-dotenv` for API key injection  |
| Async Logic  | `asyncio` / `nest_asyncio`             |

---

## 🚀 Getting Started

### ✅ Prerequisites

- Python 3.10 or higher
- Gemini API key from [Google AI Studio](https://ai.google.dev)

---

### 🛠️ Setup Instructions

#### 1. Clone the Repository

git clone https://github.com/your-username/ai-writer-agent.git
cd ai-writer-agent

2. Create & Activate Virtual Environment
bash
Copy
Edit
# Windows
python -m venv venv
venv\Scripts\activate

# macOS/Linux
python3 -m venv venv
source venv/bin/activate
3. Install Dependencies
bash
Copy
Edit
pip install -r requirements.txt
4. Create .env File
Create a file named .env in the project root with:

ini
Copy
Edit
GEMINI_API_KEY=your_gemini_api_key_here
▶️ Run the App
bash
Copy
Edit
streamlit run app.py
Then visit: http://localhost:8501

🧠 How It Works
You enter a prompt in the text area (e.g., "Write a 2 paragraph essay on Generative AI").

The agent is configured with expert writing capabilities.

The Gemini 2.0 Flash model processes your request asynchronously.

The final output is displayed inside the app.

🔍 Project Structure
bash
Copy
Edit
.
├── agents/                  # AI agent and config files
│   └── (Agent, Model, Config setup)
├── app.py                   # Main Streamlit interface
├── .env                     # Gemini API key (excluded from Git)
├── requirements.txt         # All Python dependencies
└── README.md                # You're here!
🧪 Example Prompt
text
Copy
Edit
Write a 2 paragraph essay on Generative AI.
📦 requirements.txt
Here’s what to put in your requirements.txt:

nginx
Copy
Edit
streamlit
python-dotenv
nest_asyncio
Add any other dependencies from your agents setup if needed (e.g., aiohttp, httpx, etc.)

🤖 Agent Architecture
Your custom agent is built using:

Agent: Role-based logic ("expert writer")

AsyncOpenAI: Gemini API via OpenAI-compatible protocol

OpenAIChatCompletionsModel: Gemini-backed chat model

Runner & RunConfig: Manages model execution and configs

Async Execution: Ensures non-blocking, responsive Streamlit UX

📜 License
This project is licensed under the MIT License.

👤 Author
M. Talha

Got ideas to improve this project? Open an issue or contribute via PR!

markdown
Copy
Edit

---

### ✅ Next Steps

You should:
- Replace placeholders like `your-username`, `your-profile`, `your-portfolio-link`.
- Add a `LICENSE` file (MIT if you want).
- Include a GIF/screenshot in the preview section.
- Push to GitHub and use this as your `README.md`.
