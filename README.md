# 🎫 AI ticket triage agent

Automatically classifies, prioritizes, and drafts replies for customer support tickets using a multi-agent AI pipeline.

## How it works
1. Customer support ticket is submitted
2. Agent 1 classifies the ticket (Billing / Technical / General / Urgent)
3. Agent 2 assigns priority (High / Medium / Low)
4. Agent 3 drafts a professional reply
5. All 3 steps happen in seconds — zero human intervention

## Tech Stack
- LangGraph — multi-agent orchestration
- Groq API — free LLM inference (LLaMA 3.3 70B)
- Streamlit — web UI

## Run locally
git clone https://github.com/vishu389/Ticket-Triage-Agent
cd ticket-triage-agent
pip install -r requirements.txt
streamlit run app.py
