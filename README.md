# 🔍 AI Startup Insight with Firecrawl's FIRE-1 Agent

This is a Streamlit-powered web app that extracts structured business information from company websites using Firecrawl's FIRE-1 Agent and provides AI-generated business insights using Agno's OpenAI-based agent.

## 🚀 Features

- 🔥 **Firecrawl FIRE-1 Agent**: Extracts structured data like company name, mission, product features, and contact info from websites.
- 🧠 **Agno Agent (OpenAI)**: Analyzes extracted data to provide a concise and strategic business summary.
- 📊 **Streamlit UI**: Intuitive interface with styled components and dynamic tabs for multi-site analysis.

---

## 🛠️ Installation

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/ai-startup-insight.git
cd ai-startup-insight
2. Install Dependencies
Create a virtual environment and install the required packages:

bash
Copy
Edit
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
pip install -r requirements_startup.txt
Contents of requirements_startup.txt:

Copy
Edit
firecrawl-py
streamlit
agno
openai
🔑 API Keys
You will need:

Firecrawl API Key (from Firecrawl)

OpenAI API Key (from OpenAI)

Enter these keys via the Streamlit sidebar interface. Keys are securely handled and never stored.

▶️ Running the App
bash
Copy
Edit
streamlit run ai_startup_agent.py
Then open your browser at http://localhost:8501.

🌐 Usage
Enter one or more website URLs (e.g., company homepages).

Click 🚀 Start Analysis.

View structured data + AI insights for each site in separate tabs.

📁 Project Structure
bash
Copy
Edit
├── ai_startup_agent.py         # Main Streamlit application
├── requirements_startup.txt    # Python dependencies
└── README.md                   # Project documentation
🧠 Tech Stack
Firecrawl for advanced web scraping and data structuring

Agno + OpenAI GPT-4o for AI-powered analysis

Streamlit for UI and interaction

📄 License
MIT License — feel free to use, modify, and distribute!

