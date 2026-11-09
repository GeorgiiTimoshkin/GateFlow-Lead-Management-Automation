# GateFlow-Lead-Management-Automation
Automated Lead Management System built with n8# GateFlow — Lead Management Automation

**Automated Lead Management System built with n8n, PostgreSQL and Google APIs.**

## Overview

GateFlow is an automated lead management solution designed to streamline customer inquiries, data processing and appointment scheduling.

## Features

- Automated lead capture via Webhooks
- Data validation and processing
- PostgreSQL database integration
- Duplicate submission protection
- Google Sheets integration
- Google Calendar API integration
- Automated workflow execution

## Tech Stack

- n8n
- PostgreSQL 16
- Docker
- JavaScript
- HTML / CSS
- Google Sheets API
- Google Calendar API

## Architecture

1. Customer submits a lead through the frontend.
2. Webhook receives the submission.
3. n8n validates and processes the data.
4. PostgreSQL stores the lead.
5. Google Sheets receives relevant information.
6. Google Calendar handles appointment scheduling.

## Installation

1. Install Docker and Docker Compose.
2. Deploy PostgreSQL.
3. Install and configure n8n.
4. Import the workflow JSON.
5. Configure Google API credentials.
6. Start the workflow and test the integration.

## Security

Credentials and API keys are not included in this repository. Users must configure their own credentials.

## Project Status

Portfolio project — ongoing development.n, PostgreSQL and Google APIs.
