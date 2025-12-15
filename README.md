# Smart Query Routing System (n8n + LLM + Sentiment Analysis)

## Overview

The **Smart Query Routing System** is an intelligent, AI-driven automation solution designed to classify, prioritize, and route incoming user or student queries to the appropriate departments or channels. By combining **LLM-based intent classification**, **sentiment analysis**, and **workflow orchestration using n8n**, the system ensures faster response times and reliable query handling.

This project demonstrates real-world usage of **Agentic AI concepts**, where decision-making and execution are automated end to end.

---

## Problem Statement

Organizations often receive a large volume of queries across multiple domains such as technical issues, administrative requests, payments, and academic support. Manual triage leads to delays, misrouting, and inconsistent responses.

This system automates the entire process of understanding and routing queries based on **intent, urgency, and emotional context**.

---

## Key Features

* Intelligent query classification using Large Language Models (LLMs)
* Sentiment and urgency detection (e.g., urgent vs normal)
* Automated routing based on query category and priority
* End-to-end workflow orchestration using n8n
* Structured and consistent message handling

---

## Tech Stack

* **Workflow Automation:** n8n
* **AI / NLP:** Large Language Models (LLMs)
* **Sentiment Analysis:** LLM-based sentiment classification
* **Backend Logic:** Python / n8n expressions
* **Communication Layer:** Email or internal messaging channels

---

## System Workflow

1. Incoming queries are captured through a form, API, or data source.
2. The query text is analyzed to determine sentiment and urgency.
3. An LLM classifies the query into predefined categories.
4. Routing logic assigns the query to the correct department or channel.
5. Notifications or messages are automatically sent with structured content.

---

## Query Classification Capabilities

* Intent detection across multiple categories
* Emotional tone analysis to identify critical or urgent cases
* Priority-based routing for faster issue resolution

---

## Benefits

* Reduces manual effort in query triaging
* Improves response time for high-priority issues
* Ensures consistent and reliable routing logic
* Scalable architecture for growing query volumes

---

## Use Cases

* Student or customer support systems
* IT helpdesk automation
* Academic or training institute query management
* Enterprise internal support workflows

---

## Project Timeline

**November 2025**

---

## Future Enhancements

* SLA-based escalation and reminders
* Analytics dashboard for query trends
* Integration with ticketing systems (Jira, Zendesk, Freshdesk)
* Auto-acknowledgement responses to users

---

## Author

Developed as part of hands-on work in **Agentic AI and workflow automation**, focusing on practical application of LLMs for intelligent decision-making systems.
