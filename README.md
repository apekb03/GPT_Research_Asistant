# GPT Research Assistant — LLM Function Calling with CrossRef API

A mini project that uses **OpenAI’s function calling** to create an AI-powered research assistant that can find academic articles using the **CrossRef API**. Ask natural questions like:

“Find me an article on multiple regression”, and GPT will detect the intent, call a function to fetch relevant papers, and give you a clean answer with titles and DOIs.


# Main Features

- OpenAI GPT-4 function calling
- Custom tool: `find_sources(title)`
- Integrates with [CrossRef API](https://api.crossref.org/)
- LLM selects and executes tools automatically
- Returns article titles and direct DOI links
