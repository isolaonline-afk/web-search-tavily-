---
name: web-search-tavily
description: Interroga la rete in tempo reale tramite l'API di Tavily per estrarre informazioni aggiornate.
metadata:
  require-secret: true
  require-secret-description: Inserisci la tua API Key privata di Tavily (tav_...).
---
# Web Search Tool

## Instructions
Call the run_js tool with the following exact parameters:
- script name: index.html
- data: A JSON string with the following field:
  - query: String. Il termine di ricerca estratto dalla richiesta.
