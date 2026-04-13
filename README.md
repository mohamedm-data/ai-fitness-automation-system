# ai-fitness-automation-system
## Mohamed Mohamed, Huy Minh Van, Yusuf Ali
Agentic AI Final Project.


## Overview
Gym Assistant is an AI-powered fitness automation system that acts as a virtual personal trainer. It generates personalized workout routines, nutrition plans, and equipment recommendations based on user goals — and delivers them instantly via email.

## Problem
- Users struggle to create effective workout routines
- Nutrition planning is complex and often inaccurate
- Personal trainers are expensive and not always accessible

## Solution
A fully automated AI system that:
- Understands user fitness goals via conversation
- Generates customized workout and nutrition plans
- Recommends equipment using real-world data
- Delivers results instantly via email

## System Architecture
Built using n8n as a modular automation pipeline:

User Input → AI Agent → Tools → Output (Email)

## Core Components
- AI Agent (orchestration & reasoning)
- Workout Generator
- Nutrition Calculator (TDEE + protein)
- Equipment Finder (SerpAPI)
- Gmail Automation
- Memory System (user personalization)

## Workflow
The complete automation pipeline is provided in:
workflow/workflow.json

## Demo Flow
1. User enters goal
2. AI asks follow-up questions
3. Workout plan generated
4. Nutrition calculated
5. Equipment suggested
6. Full plan emailed to user

## Tech Stack
- n8n (workflow automation)
- OpenAI API (AI agent)
- SerpAPI (equipment search)
- Gmail API (email delivery)

## Real-World Applications
- Fitness apps
- Health-tech platforms
- AI coaching systems
- Personalized wellness products

## Limitations
- Depends on user input accuracy
- API rate limits (SerpAPI)
- Requires internet connection

## Future Improvements
- Mobile app
- Wearable integration
- Computer vision for form tracking
- Multi-language support
