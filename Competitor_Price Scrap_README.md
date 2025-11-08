# KASHAN_N8N_RESUME
🧠 Competitor Price Scraper (n8n + AI Workflow)

An automated Competitor Price Scraper workflow built in n8n, designed to process and analyze pricing data using AI-powered embeddings and store structured insights in Supabase and Google Sheets.

🚀 Features

Webhook Trigger: Accepts POST requests to start the scraping workflow.

Text Processing: Splits and embeds scraped content using OpenAI Embeddings.

Vector Database: Stores processed data in Supabase for semantic search.

AI Agent: Uses LangChain RAG Agent for contextual understanding and response generation.

Google Sheets Integration: Automatically logs results and status updates.

Slack Alerts: Notifies team members in case of workflow errors.

⚙️ Tech Stack

n8n (workflow automation)

LangChain (AI reasoning and memory)

OpenAI API (embeddings model text-embedding-3-small)

Supabase (vector store for semantic search)

Google Sheets API (logging and reporting)

Slack API (real-time alerts)

📂 Workflow Overview

Webhook Trigger: Starts the flow when competitor data is received.

Text Splitter → Embeddings: Prepares and embeds content.

Supabase Vector Storage: Saves embeddings for later retrieval.

RAG Agent: Uses Anthropic model to interpret and process results.

Append Sheet: Logs the output in Google Sheets for review.

Slack Alert: Sends error notifications if something fails.

🧩 Setup Instructions

Import the .json file into n8n.

Configure credentials for:

OPENAI_API

SUPABASE_API

SHEETS_API

ANTHROPIC_API

SLACK_API

Deploy and trigger via the webhook endpoint:

POST /webhook/competitor-price-scraper

🧠 Example Use Case

Monitor and analyze competitor pricing from e-commerce or retail websites.

Store semantic representations of scraped data for AI-driven comparison and insights.

Get alerts and logs automatically without manual supervision.

📧 Author

Kashan Uddin
AI Workflow Developer | Automation Specialist
