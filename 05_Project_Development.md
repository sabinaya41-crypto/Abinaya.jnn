# 05. Project Development

## Backend Development
EduGenie was developed using FastAPI as the backend framework.

The backend provides RESTful endpoints for:
- Question answering
- Concept explanation
- Quiz generation
- Summarization
- Learning recommendations

## AI Integration

### Gemini 1.5 Pro
Gemini 1.5 Pro is used for:
- Q&A
- Summarization
- Quiz generation
- Learning paths

### LaMini-Flan-T5-783M
LaMini-Flan-T5-783M is used for simplified concept explanations.

## Module Development
The project contains separate modules for each major educational function:
- `explanation_module.py`
- `qna.py`
- `quiz_module.py`
- `summary_module.py`
- `learning_path.py`

## Quiz Development
The quiz module sends a structured prompt to the AI model and expects JSON output containing questions, options and correct answers. The response is cleaned and parsed before use.

## Frontend Development
The frontend uses HTML and CSS. It provides:
- A task dropdown
- Text area for user input
- Submit button
- Result container

Form submission sends a POST request to the FastAPI backend and the result is displayed below the input area.

## Local Execution
The project can be run locally using:

```text
uvicorn main:app --reload
```

The application can then be accessed at:

```text
http://127.0.0.1:8000
```
