# Build Prompt Engineering with Azure OpenAI Service

## Overview
This repository documents a hands-on lab focused on **prompt engineering using Azure OpenAI Service**. It demonstrates how to design effective prompts, deploy AI models, and integrate them into real-world applications.

The project showcases how **prompt structure, examples, and context** directly influence AI-generated outputs—without requiring model fine-tuning.

---

## Objectives
- Understand core **prompt engineering techniques**
- Deploy and configure **Azure OpenAI models**
- Experiment with prompts in **Azure AI Foundry Playground**
- Integrate AI into an application using **Python or C#**
- Improve outputs using:
  - System messages
  - Few-shot examples
  - Structured prompts
  - Grounding context

---

## Architecture

User Input → Prompt Design → Azure OpenAI Model → Application Layer → Response Output

---

**Core Components:**
- Azure OpenAI Service
- GPT Model Deployment (`gpt-4.1-mini`)
- Azure AI Foundry Playground
- Local Application (Python / C#)

---

## Prerequisites
- Azure Subscription (with OpenAI access)
- Azure Portal access
- Visual Studio Code
- Python 3.x or .NET SDK
- Basic understanding of APIs and prompt engineering

---

## Step-by-Step Implementation

### Step 1: Provision Azure OpenAI Resource
- Create resource via Azure Portal
- Configure region, pricing tier, and resource group
- Retrieve:
  - API Key
  - Endpoint

> ⚠️ Sensitive values are NOT included in this repo

![Step 1](https://github.com/sogcyberhub/prompt-engineering-with-azure-openai/blob/26cb808ecc2e9027781e6a60c7d9f6252197811e/001.png))

---

### Step 2: Deploy Model
- Navigate to Azure AI Foundry
- Deploy base model:
  - `gpt-4.1-mini`
- Configure deployment (e.g., `text-turbo`)

![Step 2](link-to-screenshot)

---

### Step 3: Prompt Engineering (Playground)

#### 🔹 Basic Prompt

---

Create a list of animals
Create whimsical names
Combine them into pairs
---

#### 🔹 Structured Prompt (Improved Output)
```python
# Create a list of animals
# Create whimsical names
# Combine into 25 pairs

---


