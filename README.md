.

📺 YouTube AI Agent (No-Code, GPT-Powered)
🔧 Built with n8n, OpenAI, and YouTube Transcript API

🧠 What It Does
This project is a YouTube Summarizer Agent that:

Accepts a YouTube video URL

Automatically fetches the transcript

Sends it to multiple GPT-based models

Returns a summary, key points, or Q&A from the video

It’s perfect for:

Content creators

Researchers or students

Businesses summarizing webinars or tutorials

🖼️ Visual Workflow Overview

(n8n visual workflow with YouTube transcript → OpenAI GPT → Agent responses)

🔍 Detailed Feature Breakdown
✅ Trigger: Test Mode / Webhook
Starts when you trigger a request (can be manual or from a frontend)

Ideal for testing or connecting to a user input form

📄 Transcript Extraction
Uses a custom or public YouTube Transcript API

Automatically extracts subtitles from any video with captions

💬 Multi-Model GPT Processing
Two separate OpenAI GPT-4/3.5 calls

First: Summarizes the content

Second: Extracts key points or generates a title

A third agent combines these into a polished output

🤖 AI Agent Node (Advanced)
Combines context from other models

Adds memory, logic, and advanced tool calling

Output is structured: you can display it in a chatbot or UI

🧰 Tech Stack
Tool	Use
n8n	Visual workflow logic
OpenAI	Language understanding & generation
YouTube Transcript API	Transcript extraction
Replit (optional)	Frontend demo or webhook tester

💡 Use Cases
Summarize long videos in seconds

Create blog posts or descriptions from videos

Generate FAQs based on educational videos

Business productivity: Turn training videos into notes

👨‍💻 How It Works (Client-Friendly)
🖱️ User clicks "Run" or submits a video link via UI

🔄 Workflow sends the video to YouTube Transcript API

🧠 Transcript is sent to OpenAI for summarization and processing

🤖 Combined output returned to the user (via JSON or frontend UI)

📦 Deployment / Hosting
Run locally via n8n desktop

Host on n8n.cloud or any VPS

Connect to your Replit, Carrd, or Webflow frontend

👤 About the Creator
Hi, I'm Taseen, a young no-code maker creating smart tools powered by AI and automation. I build accessible tools so anyone can use the power of AI — even without coding skills.

📬 Want a Custom Agent?
Need a YouTube summarizer or something similar?
Contact me on taseen.carrd.co

📁 Filename Suggestions (for GitHub or Replit)
Repository: youtube-ai-agent

Project name: YouTube GPT Summarizer (No-Code)

Tags: #openai, #n8n, #youtube, #gpt, #no-code, #summarizer, #ai-agent, #automation
