# News-Watcher
From basic Python → autonomous local AI workflows. All cost-free, offline, using Ollama.

**I will documenting this process on notion which will be shared**
https://www.notion.so/Singapore-News-Watcher-3019c6c05e9e80caabc6c3b5bfe839b2?source=copy_link

**Flagship Project: Singapore News Digest Agent**  
A lightweight agent that:  
- Pulls RSS feeds from CNA, Straits Times, Business Times (focusing on tech, economy, health — boosted by Singapore's 2025–2026 AI-driven growth)  
- Uses local LLM (e.g., Llama 3.2, Qwen2.5, or newer small reasoning models) to fetch, summarize, reason (CoT), score relevance, and rank top stories  
- Emails a clean daily/weekly digest via smtplib + Gmail App Password  

Built with 3–5 hrs/week over 6–10 weeks: realistic milestones, prompt experiments, debugging logs, failures → fixes.

**Core Skills Demonstrated**  
- Ollama setup & local inference  
- ReAct / LangGraph / CrewAI-style agent loops  
- Prompt engineering + chain-of-thought  
- Tools: feedparser (RSS), smtplib (email), logging, schedule/cron  
- Error handling, reliability testing, minimal viable automation  

Repo shows the full honest journey: weekly progress, code evolutions, what broke & why.  

Goal: Prove practical, private agentic AI is achievable locally in 2026.

Stack: Python • Ollama • feedparser • smtplib • logging
