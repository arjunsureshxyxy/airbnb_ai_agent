# Workflow 3 – Reply Generator Workflow

## Purpose
Generate and send the final response back to the guest.

## What this workflow does
1. Receives processed data from intent-specific workflows
2. Uses AI to generate a natural-language response
3. Formats the reply in a guest-friendly manner
4. Sends the response back via WhatsApp

## Why this workflow is separate
- Keeps response generation centralized
- Ensures consistent tone and messaging
- Allows easy changes to reply style without touching business logic

## Input
- Intent result
- Processed data from Availability, Pricing, or Booking workflows

## Output
- Final response sent to the guest
