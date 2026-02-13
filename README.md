# 🚀 AI-Powered LinkedIn Content Automation (n8n Workflow)

[![n8n Workflow](https://img.shields.io/badge/n8n-workflow-blue)](https://n8n.io/)   
[![LinkedIn API](https://img.shields.io/badge/LinkedIn-API-blueviolet)](https://www.linkedin.com/developers/)  

An end-to-end automated LinkedIn content generation system built with **n8n**, **OpenAI**, **Tavily Search API**, **Google Sheets**, and **LinkedIn API**.

This workflow automatically:
- Reads pending topics from Google Sheets
- Researches the latest updates
- Generates a high-engagement LinkedIn post using AI
- Updates the content tracker
- Publishes the post directly to LinkedIn

---

## 📌 Workflow Overview

This automation eliminates manual research and content writing by creating a fully autonomous LinkedIn publishing pipeline.

**AI-Powered LinkedIn Content Automation** is a no-code workflow built with **n8n** that automatically researches trending topics, generates engaging LinkedIn posts using **OpenAI GPT-5-mini**, updates your Google Sheets tracker, and publishes posts directly to LinkedIn — fully hands-free.

---

## ✅ Advantages

- **Time-saving**: Automates research, content generation, and publishing  
- **Consistency**: Maintains a steady LinkedIn posting schedule  
- **AI-Optimized Content**: Generates posts designed for engagement and virality  
- **Centralized Management**: Tracks topics and post status in Google Sheets  
- **Scalable**: Easily add more topics or integrate additional data sources  
- **Error-resistant**: Structured output parser ensures consistent results  

---

### Workflow Flow

flowchart LR

    A[Schedule Trigger] --> B[Read Topics (Google Sheets)]
    B --> C[Tavily Research (HTTP Request)]
    C --> D[AI Agent (OpenAI GPT-5-mini)]
    D --> E[Structured Output Parser]
    E --> F[Update Sheet (Google Sheets)]
    F --> G[Create LinkedIn Post]
