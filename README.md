# SmartDigest: AI-Based Personalized News Delivery Agent 🚀

## 🧠 Overview
SmartDigest is an intelligent AI agent built using **n8n**, **Azure OpenAI GPT-4o**, and **SerpAPI**. It:
- Fetches top news headlines based on user interests
- Summarizes them using AI
- Sends daily beautiful email digests

## 🔧 Tech Stack
- 🧱 **n8n**: No-code automation platform
- 🧠 **OpenAI GPT-4o** (via Azure): Summarization
- 🌐 **SerpAPI**: Real-time news fetching
- 📊 **Google Sheets**: User interest data
- 📧 **Gmail API**: Email delivery

## 🔄 Workflow
1. Fetch user data (email, topic) from Google Sheets
2. Loop through each user
3. Use SerpAPI to fetch news by topic
4. Summarize news using GPT-4o
5. Format into HTML using code
6. Send via Gmail

## 📎 Sample Output
See [`assets/sample-email.html`](assets/sample-email.html)

## 📊 Use Cases
- Daily news for professionals and students
- Company newsletters
- Domain-specific digests (e.g., AI, Politics, Bollywood)

## 🔮 Future Scope
- Telegram / WhatsApp digests
- Sentiment filtering
- News dashboard with user engagement stats
- B2B branded newsletters

## 🧠 Built With
- Azure OpenAI
- SerpAPI
- Google Workspace APIs
- n8n Cloud
- JavaScript (for formatting)

## 👨‍💻 Author
**Mahir Desai**  
Hackathon Project Submission – 2025 🚀
