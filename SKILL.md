---
name: web-search-brave
description: Interroga l'indice globale e indipendente di Brave Search per trovare notizie e documentazione tecnica in tempo reale.
metadata:
  require-secret: true
  require-secret-description: Inserisci la tua API Key privata di Brave Search.
---
# Brave Web Search Tool

## Instructions
Call the run_js tool with the following exact parameters:
- script name: index.html
- data: A JSON string with the following field:
  - query: String. Il termine di ricerca mirato da cercare sul web.
