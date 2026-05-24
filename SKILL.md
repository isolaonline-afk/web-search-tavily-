---
name: web-search-exa
description: Interroga la rete tramite il motore neurale di Exa.ai per estrarre contesti ad altissima densità informativa.
metadata:
  require-secret: true
  require-secret-description: Inserisci la tua API Key privata di Exa.ai.
---
# Exa Neural Search Tool

## Instructions
Call the run_js tool with the following exact parameters:
- script name: index.html
- data: A JSON string with the following field:
  - query: String. Il quesito concettuale o l'argomento da cercare in rete.
