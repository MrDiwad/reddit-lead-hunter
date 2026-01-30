# Reddit Lead Hunter (n8n + AI)
This system automatically hunts through subreddits and drops the best opportunities straight into Notion CRM.

# How it works
RSS over APIs: . I used free Reddit RSS feeds—simple, fast, and it just works.

The "BS" Filter (Regex): Before bothering the AI, the bot checks posts for specific keywords like hiring, help, or problem. This keeps my token usage low.

AI Brain (Llama 3): If a post passes the filter, the AI (via Groq) takes over. It reads the content and decides if it is a possible lead.

Contextual Memory: The bot has a "short-term memory," so it stays on track during processing.

Notion CRM: Everylead lands in a clean Notion table with a direct link and a quick AI summary of why it’s worth to take a closer look at it.

# Tech Stack
Automation: n8n

AI/LLM: Groq (Llama 3)

Database: Notion

Data Source: Reddit RSS
