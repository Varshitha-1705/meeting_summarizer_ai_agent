# 🧠 Meeting Summarizer AI Agent
AI-powered meeting summarizer that converts transcripts or audio into concise summaries, key decisions, and action items using OpenAI GPT and LangChain.


## 🚀 Overview
This project uses OpenAI GPT and LangChain to analyze meeting data and generate structured summaries.  
It supports both text and audio inputs (via speech-to-text).


## 🧩 Tech Stack
- Python  
- OpenAI API  
- LangChain  
- Pandas, NumPy  
- (Optional) Whisper / Streamlit  



## ✨ Features
- Summarizes long meetings into short points  
- Extracts action items and decisions    
- Custom summary styles (bullet, paragraph)



## ⚙️ How to Run
1. Clone the repo  
   git clone https://github.com/Varshitha-1705/meeting-summarizer-ai-agent.git

2. Install dependencies
   pip install -r requirements.txt

3. Add your OpenAI API key
    jupyter notebook meeting_summarizer_ai_agent.ipynb


🧾 Example Output

  Input:

    “Team decided to launch next month. Marketing content due next week.”

  Summary:

    Product launch scheduled for next month
    Marketing content due next week

  Action Items:

     Prepare marketing content
     Plan launch event
