# AI Calendar Assistant Workflow

## Overview
This project is an **AI-powered calendar automation workflow** built using **n8n**, **OpenAI ChatGPT**, and **Google Calendar**.  
It allows users to **automatically schedule events** through chat commands, dynamically checking availability and creating events without manual effort.

## Features
- Integrates **OpenAI ChatGPT** to understand user input and generate event details.
- Connects to **Google Calendar** to automatically create events.
- Handles **dynamic start and end times** for meetings.
- Provides **error handling** and ensures correct scheduling.
- Easy to customize and extend for other calendar automation tasks.

## Workflow Details
- Workflow trigger: Chat message.
- AI Node: Processes user input and generates event data.
- Google Calendar Node: Creates events with AI-generated times and descriptions.

## Files
- `My workflow.json` – Exported n8n workflow file.  
- `Screenshot 2025-08-16 161803.png & Screenshot 2025-08-16 162234.png` – Screenshots of the workflow nodes in n8n for reference.  

## How to Use
1. Import the `My workflow.json` file into your **n8n instance**.
2. Configure your **Google Calendar credentials**.
3. Start the workflow and send a chat command to create events.
4. Check your Google Calendar to see events scheduled automatically.

## Tech Stack
- **n8n** – Automation platform  
- **OpenAI GPT** – AI for natural language understanding  
- **Google Calendar API** – Event creation and management  

## Demo
Screenshots of the workflow are available to understand the node connections and logic.

