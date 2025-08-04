# NeoScout

🚀 NeoScout: Scout Smarter, Search Sharper Empower next-gen decision-making with NeoScout — your AI-enhanced research agent built on PydanticAI's intelligent workflows and Tavily's real-time search capabilities. Whether it's scouting talent, trends, or technologies, NeoScout transforms how you discover insights with precision and speed.

🌐 From raw query to refined knowledge, NeoScout bridges intelligent search with structured responses — so you can focus on what matters most: making the next move count.

## 🌟 Features

- 🔍 Semantic query interpretation for deeper insight extraction
- ⚙️ Modular agent architecture powered by Pydantic AI
- 🧠 Real-time search enrichment via Tavily
- 📦 Lightweight deployment on [Streamlit](https://streamlit.io)
- 🛡️ Secure config management and environment handling

## 📁 Project Structure

```bash
├── app.py                  # Streamlit entrypoint
├── agent_utils.py          # Agent setup, Tavily + Pydantic logic
├── requirements.txt        # Dependencies
├── README.md               # Project overview
├── .gitignore              # Repo hygiene
└── LICENSE                 # MIT License
```

## 🛠️ Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/varshithrevally/NeoScout.git
cd NeoScout
```

### 2. Create Virtual Environment (recommended)

```bash
python3 -m venv venv
source venv/bin/activate  # or venv\\Scripts\\activate on Windows
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Add Tavily & Pydantic API Keys

Create a `.env` file:

```dotenv
TAVILY_API_KEY=your_tavily_key
GROQ_API_KEY=your_groq_key
```

### 5. Run the App Locally

```bash
streamlit run app.py
```

## 🌍 Live Demo

🔗 Try it live: [neoscout.streamlit.app](https://neoscout.streamlit.app)

## 🧪 Example Usage

Search for:  
> *"Top 5 open-source LLMs for real-time applications"*  
NeoScout will return structured, cited insights based on fresh web content.

## 💡 Use Cases

| Area             | Impact                                        |
|------------------|-----------------------------------------------|
| Talent Scouting  | Identify emerging developers, startups, trends|
| Competitive Intel| Monitor tech advances, product updates        |
| Market Research  | Digest niche communities & reports            |

## 🧰 Built With

- Python
- Streamlit
- Tavily API
- Pydantic AI
- Git & GitHub

This project is licensed under the MIT License.

---
