# Airbnb AI Agent (n8n)

This project showcases a modular AI-powered Airbnb assistant built using n8n.
The agent automates guest conversations over WhatsApp using AI-driven intent
detection and response generation.

---

## Architecture Overview

The system is designed as multiple independent workflows:

1. WhatsApp Intake
2. Intent Detection
3. Reply Generator
4. Intent-specific handlers

Each workflow has a single responsibility, making the system easier to extend
and maintain.

---

## Implemented Workflows

### Workflow 1 – WhatsApp Intake
- Receives guest messages via WhatsApp
- Structures incoming data
- Sends initial acknowledgment

### Workflow 2 – Intent Detection
- Uses AI to understand guest intent
- Routes requests to appropriate workflows

### Workflow 3 – Reply Generator
- Generates dynamic responses using AI
- Centralizes message formatting

### Workflow 4 – Intent-specific Workflows
- Availability inquiries
- Greetings
- Fallback handling

---

## Tech Stack
- n8n (workflow orchestration)
- WhatsApp integration
- AI / LLM for intent and responses

---

## Notes
- Secrets and credentials are excluded
- Focus is on workflow design and AI orchestration
