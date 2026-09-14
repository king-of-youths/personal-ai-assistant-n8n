# Personal AI Assistant — n8n

An AI-powered personal assistant built with n8n and Google Gemini.

The assistant can answer questions, remember conversation context, search a contact database, create Google Calendar events, and send Gmail messages automatically.

## Project Overview

This project demonstrates how AI agents can interact with external services and perform real-world automation tasks.

The assistant is designed to help users with:

* AI and technology questions
* Conversation memory
* Contact lookup
* Calendar scheduling
* Email communication
* Date and time handling
* Automated tool execution

## Workflow

User Request Form
↓
Prepare Request
↓
Prepare Date & Session
↓
Personal AI Assistant
↓
Assistant Response

The AI Agent is connected to:

* Google Gemini
* Conversation Memory
* Google Sheets Contact Database
* Google Calendar
* Gmail

## Technologies Used

* n8n
* Google Gemini
* Google Sheets
* Google Calendar
* Gmail
* Webhooks / Forms
* JSON
* APIs
* AI Agents
* Automation workflows

## Key Features

### AI Assistant

The assistant uses Google Gemini to understand user requests and provide helpful responses.

### Conversation Memory

The assistant can remember information during a conversation using n8n Simple Memory and a session ID.

### Contact Database

Google Sheets is used as a contact database.

Before sending an email to a person identified by name, the assistant searches the contact database for the correct email address.

### Google Calendar

The assistant can create calendar events using the requested date and time.

The workflow uses the Africa/Lagos timezone and converts relative dates such as "tomorrow" into exact calendar dates.

### Gmail

The assistant can send emails automatically using verified contact information from the contact database.

### Safety Rules

The AI agent is instructed not to invent contact information and not to repeat successful calendar or email actions unnecessarily.

## Testing

The workflow was tested with:

* Basic AI questions
* Conversation memory
* Contact lookup
* Calendar event creation
* Gmail sending
* Missing contact handling
* Relative date handling
* Autonomous tool execution

All major Version 1 features were successfully tested.

## Screenshots

### Full Workflow

Add your screenshot:

`01-Personal-AI-Assistant-Full-Workflow.png`

### AI Agent

Add your screenshot:

`02-Personal-AI-Assistant-AI-Agent.png`

### Contact Database

Add your screenshot:

`03-Contact-Database.png`

### Calendar Execution

Add your screenshot:

`04-Successful-Calendar-Execution.png`

### Working Assistant

Add your screenshot:

`05-Working-Personal-AI-Assistant.png`

## Future Improvements

Planned improvements include:

* WhatsApp integration
* Supabase database
* Web search
* Document and PDF knowledge
* RAG
* Advanced email automation
* Better error handling
* Logging and monitoring
* Automated notifications

## Project Status

Version 1 — Completed ✅

This project is part of my journey into AI Automation Engineering.
