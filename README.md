# AI Workflow for Identifying Declining FOSS Dependencies

An automated AI-driven workflow for analysing Free and Open Source Software (FOSS) dependencies, identifying end-of-life (EOL) and deprecated components, and prioritising high-risk dependencies for remediation.


## Project Overview

Modern software systems often rely on hundreds of third-party open-source dependencies. While tools such as JFrog provide dependency reports, these reports frequently lack critical contextual information, including:

- End-of-life (EOL) status  
- Active maintenance and support status  
- Security vulnerabilities and real-world exploitability  
- Risk prioritisation based on impact and usage  

Manually researching this information using large language models (LLMs) is time-consuming, repetitive, and error-prone.  

This project introduces an automated AI workflow that performs this research end-to-end with minimal human input, producing a ranked, explainable report of the most critical dependencies to address.



## Objectives

The primary goals of this project are to:

- Automate dependency research using an LLM  
- Enrich raw dependency data with:
  - EOL and support status  
  - Security risks and known CVEs  
  - Maintenance cadence and ecosystem health  
- Filter and prioritise deprecated dependencies  
- Generate a final ranked report explaining why certain dependencies require urgent attention  


## Technology Stack

- **n8n** – Open-source workflow automation platform  
- **Azure OpenAI (LLM)** – Automated research, analysis, and report generation  
- **Web Search API** – Retrieval of authoritative sources (e.g. CVEs, vendor documentation)  
- **PostgreSQL** – Storing dependency reports and researched data  

## Author
Dakshit Singhal  
BSc (Hons) Computer Science  
University of Manchester
