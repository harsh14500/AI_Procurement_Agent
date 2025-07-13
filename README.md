# AI Procurement Agent (LangChain + CSV + Local LLM)

### Project Timeline
- Developed: July 2024 (not uploaded earlier)
-  Uploaded to GitHub: July 2025

---

## Project Overview

This project is an AI-powered assistant that helps analyze procurement datasets using **natural language questions** like:

- “Top 5 agencies”
- “Which ministry had the highest procurement?”
- “What is the total spend by XYZ department?”

It uses **LangChain + Pandas Agent** to interpret the data and now supports **local LLMs using Ollama** (no paid OpenAI key needed!).

---

## Tech Stack

-  LangChain
-  PandasAgent
-  CSV as data source
-  Local LLM (LLaMA 3 via Ollama)
-  No OpenAI key required (offline support)

---

## Files Included

- `procurebot_agent.py` → Main agent script
- `data.csv` → Procurement dataset
- `requirements.txt` → Project dependencies
- `README.md` → Documentation

---

## How it Works

1. Loads the procurement CSV file.
2. Uses LangChain agent to understand your question.
3. Queries the dataset using Pandas under the hood.
4. Responds in simple human language using a local LLM model (LLaMA 3 via Ollama).

---

## sing with Ollama (LLaMA 3)

You don’t need any API key!  
Just install [Ollama](https://ollama.com/) and pull the model:

```bash
ollama run llama3
