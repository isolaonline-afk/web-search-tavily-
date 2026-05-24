---
name: web-search-tavily
description: Real-time web search using Tavily. Use this skill whenever the user asks to search the web, find current news, recent events, or updated information.
metadata:
  require-secret: true
  require-secret-description: Inserisci la tua API Key privata di Tavily.
---
# Tavily Web Search Tool

## Instructions
Call the run_js tool with the following exact parameters:
- script name: index.html
- data: A JSON string with the following field:
  - query: String. Il termine di ricerca mirato da cercare sul web.
