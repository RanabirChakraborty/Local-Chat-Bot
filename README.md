# Local-Chat-Bot

This repository contains an **LLM API service** designed to provide AI-generated text responses. It is built using **FastAPI** and runs a **local LLM model**, optimized for natural language processing tasks such as:
- **Text generation**
- **Summarization**
- **Chatbot interactions**

The API supports **JSON-based queries** and can be integrated into automation workflows, including **Ansible Middleware**.

## How to Run the LLM on Your System

1. Run the **`ai_playbook.yml`** to set up the environment.
2. Once completed, you can send queries via the **command line** or through a **UI interface**.

### Example API Request:
```sh
curl -X POST "http://localhost:8000/generate" \
     -H "Content-Type: application/json" \
     -d '{"prompt": "What is AI?"}'
```
![Response](https://github.com/RanabirChakraborty/Local-Chat-Bot/blob/main/images/reponse.png)
