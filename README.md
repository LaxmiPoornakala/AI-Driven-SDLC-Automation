# AI-Driven SDLC Automation using Multi-Agent Systems

## Overview
This project implements an **AI-powered Software Development Life Cycle (SDLC) automation system** using multi-agent orchestration frameworks:

- Microsoft AutoGen  
- LangGraph  
- LangChain  
- GPT-based LLM configuration  

The system simulates **Waterfall and Agile (Scrum) workflows**, where autonomous AI agents collaborate to generate requirements, sprint plans, architecture design, testing strategies, and documentation.

## Problem Statement
Traditional SDLC processes require coordination across multiple stakeholders, leading to communication overhead and planning inefficiencies.

This project explores:

> Can multi-agent LLM systems simulate structured SDLC workflows efficiently and autonomously?

## System Architecture

Role-based AI agents simulate real SDLC stakeholders:

- Customer – Provides initial requirements  
- Product Owner – Creates user stories & backlog  
- Scrum Master – Organizes sprints  
- Developer – Generates implementation plan  
- Architect – Designs system architecture  
- QA Engineer – Creates test cases  
- Documentation Engineer – Produces documentation  

## Workflow Modes Implemented

1. **Linear Execution** – Sequential agent flow  
2. **Round-Robin Execution** – Iterative agent collaboration  
3. **Graph-Based Execution (LangGraph)** – Controlled, conditional orchestration  

## Tech Stack

- Python  
- AutoGen  
- LangGraph  
- LangChain  
- OpenAI LLMs  
- Prompt Engineering  

## Key Features

- Automated requirement refinement  
- User story & backlog generation  
- Sprint planning simulation  
- Architecture & test case generation  
- Multi-agent orchestration comparison  
- Execution efficiency analysis  

## Results & Insights

- Graph-based orchestration provided better workflow control.
- Round-robin improved refinement but increased coordination overhead.
- Structured prompt design significantly improved output consistency.
- Multi-agent systems can realistically simulate SDLC planning stages.

## How to Run

- Install autogen langchain langgraph openai
- Configure your API key in the llm_config file and run the notebooks.

## Skills Demonstrated

- Multi-Agent AI System Design
- Workflow Orchestration
- Prompt Engineering
- SDLC Modeling
- Experimental Evaluation of AI Systems

## Use Cases

- AI-powered project management tools
- Agile automation platforms
- Intelligent DevOps planning systems
- Enterprise workflow automation