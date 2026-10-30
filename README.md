# EcoSort AI — Smart Waste Segregation & Sustainability Assistant

EcoSort AI is an educational prototype for helping users understand how common waste items may be sorted into waste streams. It is aligned with **UN Sustainable Development Goal 12: Responsible Consumption and Production**.

## Problem
Incorrect waste segregation can contaminate recycling and make disposal confusing. EcoSort AI demonstrates a simple decision-support workflow that provides a sample category, explanation, suggested next step, and confidence/uncertainty note.

## Features
- Select from sample waste items and view a suggested category.
- Read a brief explanation and disposal suggestion.
- Show an uncertainty message for unclear/unknown items rather than forcing a classification.
- Review the workflow and responsible-AI principles: fairness, transparency, ethics, and privacy.
- Includes prompt/workflow notes and the project presentation.

## Technologies
- HTML
- CSS
- JavaScript
- Prompt/workflow design concepts

## Run locally
1. Download or clone this repository.
2. Open `index.html` in a modern web browser.
3. Select a sample item and choose **Analyze with AI workflow**.

No package installation is required for this static demo.

## Important limitation
This is a **prototype demonstration using predefined sample-item mappings**. It does not currently call a live generative-AI service, use a trained image-recognition model, or connect to a retrieval-augmented generation (RAG) system. The interface illustrates a possible decision-support workflow; it is not authoritative local waste-disposal guidance. Follow local municipal rules, especially for batteries, electronics, chemicals, and other hazardous waste.

## Responsible AI considerations
- **Transparency:** explain the suggested category and show uncertainty where appropriate.
- **Safety:** avoid guessing when an item is unclear and recommend human/local verification.
- **Privacy:** the current demo does not need personal data or uploaded images.
- **Fairness:** future versions should be tested with varied items and real-world conditions.

## Sustainability alignment
Primary SDG: **SDG 12 — Responsible Consumption and Production**. The project aims to support awareness of waste segregation and more responsible disposal decisions. No measured environmental impact is claimed; impact is anticipated and would require user testing and measurement.

## Files
- `index.html` — interactive prototype
- `prompt-workflow.txt` — prompt/workflow notes
- `project-presentation.pptx` — project presentation

## Author
Greeshma Sri Komarala  
B.Tech, Computer Science and Engineering  
Tirumala Engineering College  
Register No.: 23NE1A05Q3
