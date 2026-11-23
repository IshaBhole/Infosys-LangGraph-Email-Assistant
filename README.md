# Infosys LangGraph Email Assistant

An AI-powered email assistant developed as part of **Infosys Springboard Internship 6.0**, focused on building an ambient agent using LangGraph, intelligent email workflows, tool integration, and memory-based interaction.

## Overview

The **LangGraph Email Assistant** is a collaborative internship project exploring how AI agents can automate and assist with email-related tasks. The project uses LangGraph to structure agent workflows, integrate tools, manage state, and support human-in-the-loop interactions.

My repository contains my branch and contributions from the collaborative internship project.

## Project Objectives

- Explore agentic AI workflows using LangGraph.
- Develop intelligent email processing and triage workflows.
- Integrate tools into AI agent workflows.
- Implement human-in-the-loop interaction.
- Explore memory and personalized responses.
- Integrate Gmail and Google Calendar APIs.

## Milestones & Work

### Milestone 1 – Email Triage Workflow

- Developed an email triage workflow using an LLM.
- Integrated Gemini for AI-based email processing.
- Implemented structured email categorization and routing.
- Worked with categories such as `ignore`, `notify_human`, and `respond`.
- Integrated tool-based workflow logic.
- Evaluated workflow predictions against labeled email data.

### LangGraph Workflow Development

- Worked with graph-based agent orchestration.
- Implemented nodes and workflow transitions.
- Explored conditional routing and state management.
- Structured agent execution using LangGraph.

### Human-in-the-Loop & Memory

- Implemented a human-interaction node in the workflow.
- Demonstrated user preference correction.
- Used memory to maintain a personalized name preference.
- Integrated human input into subsequent agent responses.

### Gmail & Google Calendar Integration

- Integrated the Gmail API for sending emails.
- Integrated the Google Calendar API for creating calendar events.
- Implemented Google OAuth authentication.
- Developed tool functions for email and calendar operations.

## Technologies Used

- **Python**
- **LangGraph**
- **LangChain**
- **Google Gemini**
- **Gmail API**
- **Google Calendar API**
- **Google OAuth 2.0**
- **Pandas**
- **Git & GitHub**

## Project Structure

```text
Infosys-LangGraph-Email-Assistant/
│
├── data/
├── notebook/
├── src/
├── app.py
├── memory.py
├── memory.db
├── tools.py
├── test_tools.py
├── requirements.txt
├── test.txt
├── .gitignore
└── README.md
```

## Setup

### 1. Clone the repository

```bash
git clone https://github.com/IshaBhole/Infosys-LangGraph-Email-Assistant.git
cd Infosys-LangGraph-Email-Assistant
```

### 2. Set up Python

Create and activate a virtual environment:

```bash
python -m venv venv
```

Windows:

```bash
venv\Scripts\activate
```

### 3. Install dependencies

Install the project dependencies listed in `requirements.txt` after verifying that the file has been populated.

### 4. Configure Google API credentials

Google API integrations require OAuth credentials for Gmail and Google Calendar.

- Configure the required Google APIs in Google Cloud.
- Set up OAuth credentials.
- Store credential and token files locally.
- Never commit credential files, access tokens, or secrets to GitHub.

### 5. Run the application

Run the application using the appropriate Python entry point after configuring the dependencies and credentials.

## Internship

**Program:** Infosys Springboard Internship 6.0  
**Project:** Building an Ambient Agent with LangGraph for an Email Assistant  
**Project Type:** Collaborative internship project

## Author

**Isha Bhole**

[GitHub Profile](https://github.com/IshaBhole)

[Project Repository](https://github.com/IshaBhole/Infosys-LangGraph-Email-Assistant)

---

This repository contains my branch and work contributed to the collaborative internship project.
