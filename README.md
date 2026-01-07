# Airbnb AI Agent (n8n)

This project demonstrates a modular AI-powered Airbnb assistant built using **n8n**.
The agent automates guest communication over WhatsApp by detecting intent and
responding intelligently using AI.

---

## Project Objective
To design and implement a no-code / low-code AI agent that can:
- Receive guest messages via WhatsApp
- Understand guest intent using AI
- Route requests to dedicated business-logic workflows
- Generate and send natural language replies automatically

---

## Architecture Overview
The system is built as a set of independent workflows, each with a single
responsibility. This modular design improves clarity, scalability, and
maintainability.

---

## Implemented Workflows

### Workflow 1 – WhatsApp Intake
- Receives incoming WhatsApp messages
- Extracts and structures guest data
- Sends an initial acknowledgment response

### Workflow 2 – Intent Detection
- Analyzes guest messages using AI
- Identifies the intent of the request
- Routes requests to the appropriate workflow

### Workflow 3 – Reply Generator
- Generates consistent, human-like responses using AI
- Formats messages before sending to WhatsApp
- Centralizes all outbound communication logic

### Workflow 4 – Availability Workflow
- Handles guest queries related to property availability
- Applies availability logic or rules
- Prepares responses for the Reply Generator

### Workflow 5 – Pricing Workflow
- Handles pricing and cost-related inquiries
- Applies pricing logic or calculations
- Sends structured output to the Reply Generator

### Workflow 6 – Booking Request Workflow
- Handles booking-related guest requests
- Validates booking requirements
- Prepares next steps or confirmations

---

## Technology Stack
- **n8n** – Workflow orchestration
- **WhatsApp integration** – Guest communication
- **AI / LLM** – Intent detection and response generation

---

## Repository Structure

