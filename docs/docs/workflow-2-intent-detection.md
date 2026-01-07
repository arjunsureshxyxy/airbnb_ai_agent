# Workflow 2 – Intent Detection Workflow

## Purpose
Identify the intent of the guest message received via WhatsApp.

## What this workflow does
1. Receives structured guest input from the WhatsApp Intake workflow
2. Sends the message content to an AI model
3. Analyzes the guest’s intent
4. Routes the request to the appropriate intent-specific workflow

## Supported Intents
- Availability queries
- Pricing-related questions
- Booking requests
- Fallback / unknown intent

## Why this workflow is important
This workflow acts as the decision-making layer of the AI agent.
It ensures that each guest request is handled by the correct business logic.

## Output
- Identified intent
- Clean, structured data passed to the next workflow
