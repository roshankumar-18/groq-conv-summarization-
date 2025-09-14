# groq-conv-summarization-
Groq API project: Conversation management + JSON schema extraction

# Groq API Project: Conversation Summarization & Classification

This project demonstrates how to use **Groq APIs (OpenAI SDK compatible)** to:
1. **Manage conversation history with summarization**  
   - Maintain chat history
   - Summarize after every k turns
   - Truncate by message count or character length

2. **Extract structured data using JSON schema classification**  
   - Extracts fields: `name, email, phone, location, age`
   - Uses OpenAI function-calling (Groq compatible) for strict JSON outputs
   - Validates results against schema

---

## 🚀 Features
- Conversation manager with customizable summarization frequency (`k` runs)
- Truncation by number of turns or max character length
- Automatic structured extraction of user details from chats
- No frameworks: only **Python + openai (Groq SDK)**

---
