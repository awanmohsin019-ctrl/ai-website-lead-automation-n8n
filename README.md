# ai-website-lead-automation-n8n
This repository contains a production-ready automation workflow built using n8n that transforms website chat inquiries into structured CRM entries and automated follow-up actions.
# Overview

The system acts as an intelligent lead-processing engine capable of:

Handling incoming website chat requests via webhook

Generating AI-based structured responses

Extracting intent, lead score, and follow-up indicators

Logging qualified leads into CRM (Google Sheets)

Sending automated follow-up emails

Maintaining complete administrative logs
Architecture

Single Workflow Structure:

Chat Intake (Webhook + AI Processing)

Lead Qualification (Conditional Logic)

CRM Logging (Google Sheets Integration)

Follow-Up Automation (Email Node)

Admin Logging (Conversation & Execution Tracking)
Core Features

Structured AI JSON parsing

Conditional branching logic

Cross-node data referencing

Error-safe execution using optional chaining

Clean HTTP response lifecycle (single webhook response)

Modular and scalable workflow design
Use Cases

Educational institutions

Online academies

SaaS inbound lead capture

Agency automation systems

Service-based businesses
Tech Stack

n8n

AI Model Integration (structured output parsing)

Google Sheets API

SMTP / Gmail integration

Webhook-based HTTP handling
Future Extensions

Multi-step delayed follow-up sequences

WhatsApp integration

CRM integrations (HubSpot, Zoho, etc.)

Analytics dashboard

Lead scoring refinement engine
License

Open for learning and demonstration purposes
