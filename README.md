# Google ADK Multi-Agent Lab

Hands-on Google Cloud ADK project featuring multi-agent workflows, Gemini-powered agents, fact-checking, and Google Search grounding.

## 🚀 Project Overview

This project demonstrates how to build and test AI agents using Google's Agent Development Kit (ADK).

The lab includes:

- Single-agent applications
- Multi-agent workflows
- Fact-checking agents
- Revising agents
- Google Search grounding
- Structured outputs with Pydantic
- ADK Dev UI interaction

## 🧩 Multi-Agent Architecture

The project uses multiple agents working together:

1. *Google Search Agent*
   - Retrieves external information from the web

2. *Critic Agent*
   - Evaluates factual accuracy of responses

3. *Reviser Agent*
   - Corrects inaccurate or misleading outputs

4. *Verification Workflow*
   - Displays event traces and reasoning process

## 🛠️ Technologies Used

- Google Cloud
- Vertex AI
- Gemini 3 Flash Preview
- Google ADK
- Python
- Multi-Agent Systems
- Google Search Grounding
- Cloud Shell

## ✨ Features

- Multi-agent verification workflow
- Google Search grounding
- Fact-checking and claim analysis
- Event trace visualization
- Agent collaboration with ADK
  
## 📸 Demo Screenshots

### 🔍 Multi-Agent Fact Checking

![Multi-Agent Fact Checking](Multi-Agent%20Fact%20Checking.png)

---

### 🧠 Agent Verification Workflow

![Agent Verification Workflow](Agent%20Verification%20Workflow.png)

---

### 🌐 Google Search Agent

![Google Search Agent](Google%20Search%20Agent.png)

---

### 💻 Terminal Execution

![Terminal Execution](Terminal%20Execution.png)

---
💡 Example Scenario

Input:
```bash
Earth is further away from the Sun than Mars.
```

### Agents automatically:

Detect factual inaccuracies
Verify information with Google Search
Generate a corrected response
## 📂 Project Structure

```bash
app_agent/
llm_auditor/
my_google_search_agent/
adk_utils/
```

### 🔍 Multi-Agent Workflow

The project includes a multi-agent architecture:

critic_agent → checks factual correctness
reviser_agent → rewrites incorrect answers
Google Search → provides grounding and verification


### 🖥️ ADK Dev UI Preview

This project was tested using the Google ADK Dev UI on Google Cloud Shell.

### 📚 Learning Outcomes

Building AI agents with ADK
Creating multi-agent systems
Implementing fact-checking workflows
Using structured schemas with Pydantic
Grounding LLM responses with Google Search

### 👩‍💻 Author

Beyza UZUN
