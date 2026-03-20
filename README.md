# rag-document
rag
--------------------------------------

Content Evaluator Pro 🚀

Content Evaluator Pro is a powerful, client-side web application designed to analyze and optimize written content for both Traditional Search Engines (SEO) and LLM Discoverability (AI Search Systems like ChatGPT, Gemini, and Claude).

As search evolves from traditional keyword indexing to generative AI answers, content must be optimized for both paradigms. This tool bridges that gap.
--------------------------------------------

✨ Features

Dual-Engine Analysis: Evaluates content against standard Google SEO heuristics AND modern LLM context-retrieval patterns (Entity density, Q&A clarity, structured knowledge).

Multi-Provider Support: Bring your own API key. Supports OpenAI, Google Gemini, and OpenRouter (Claude, Llama, etc.).

Dynamic Scoring: Visual gauges (powered by Chart.js) providing an Overall Score, SEO Score, and LLM Score.

Actionable Insights: Categorized feedback detailing exactly where your content lacks depth, semantic richness, or E-E-A-T signals.

1-Click Auto-Improve: Instantly generates a perfectly optimized draft of your article based on the analysis suggestions.

Privacy First (No Database): 100% client-side execution. Your API keys are stored only in your browser's active session and are never saved to a database or external server.
----------------------------------------------------------

🛠️ Tech Stack

This project is built for maximum portability and speed as a Single Page Application (SPA):

Frontend: HTML5, Vanilla JavaScript

Styling: Tailwind CSS (via CDN)

Data Visualization: Chart.js (via CDN)

AI Integration: Direct REST API calls to OpenAI, Google Gemini, and OpenRouter via browser fetch.
=--------------------------------------------------------------

 📖 How to Use

Configure your API: Select your preferred AI provider (OpenAI, Gemini, OpenRouter), select your model, and paste your API key.

Input Content: Add your article's title and paste the body of your text.

Select Mode: Choose to optimize for SEO, LLMs, or Both.

Analyze: Click "Analyze Content". The system will process the text and generate your scores and detailed feedback.

Auto-Improve: Review the exact improvement suggestions, and optionally click "Auto Improve Article" to have the AI rewrite the content applying all best practices.
--------------------------------------------------------------------

🔒 Security & Privacy

Your API keys are safe. This application does not have a backend server or database. API keys entered into the UI are kept temporarily in memory to make direct requests to the AI providers. If you refresh the page, the key is cleared. We highly recommend generating a scoped API key with a strict spending limit for use in client-side applications.
