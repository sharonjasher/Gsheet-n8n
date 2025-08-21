# Gsheet Automation

[![n8n](https://img.shields.io/badge/built%20with-n8n-3ebd70.svg)](https://n8n.io/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

---

## Table of Contents

- [Project Overview](#project-overview)
- [Motivation](#motivation)
- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Workflow Details](#workflow-details)
- [License](#license)
- [Author & Contact](#author--contact)
- [Acknowledgements](#acknowledgements)

---

## Project Overview

**Gsheet Automation**  
An n8n workflow that retrieves reviews from a Google Sheet, analyzes each review’s sentiment using OpenAI’s GPT-4O-mini language model, and updates the sheet with the sentiment analysis result for each row.

---

## Motivation

Organizations often need to analyze customer feedback quickly for sentiment insights. This workflow automates the process directly within Google Sheets, enabling efficient batch sentiment classification without manual effort.

---

## Features

- Manual trigger for on-demand execution
- Reads rows containing reviews from a specified Google Sheet
- Analyzes sentiment of each review as Positive, Neutral, or Negative using GPT-4O-mini
- Updates or appends sentiment results back to the same Google Sheet
- Uses secure OAuth2 authentication for Google Sheets and OpenAI APIs

---

## Prerequisites

- n8n instance (Cloud or self-hosted)
- Google Sheets OAuth2 credentials configured in n8n
- OpenAI API key with GPT-4O-mini access
- Node.js installed if self-hosting n8n
- Modern browser for n8n Editor

---

## Installation

