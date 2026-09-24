# 03. Project Design

## System Overview
EduGenie uses a web frontend connected to a FastAPI backend. The backend routes each selected task to the appropriate AI module.

## Basic Workflow

User Input
→ HTML/CSS Frontend
→ FastAPI Backend
→ Selected AI Module
→ AI Model
→ Generated Result
→ Result displayed to User

## Main Modules

### 1. Explanation Module
Uses LaMini-Flan-T5-783M to provide simplified explanations of concepts.

### 2. QnA Module
Uses Gemini 1.5 Pro for academic and general question answering.

### 3. Quiz Module
Uses Gemini to generate three MCQs with four options each and returns structured output.

### 4. Summary Module
Uses Gemini to summarize long paragraphs while retaining important information.

### 5. Learning Path Module
Uses Gemini to create a structured beginner-to-advanced learning path with useful resources.

## API Endpoints
- `/qa`
- `/explain`
- `/quiz`
- `/summarize`
- `/learn/recommendations`

## Folder Architecture

```text
EduGenie/
├── main.py
├── explanation_module.py
├── qna.py
├── quiz_module.py
├── summary_module.py
├── learning_path.py
├── templates/
│   └── index.html
├── static/
│   └── style.css
└── requirements.txt
```
