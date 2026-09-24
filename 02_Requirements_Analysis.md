# 02. Requirements Analysis

## Functional Requirements
EduGenie should provide the following functions:

1. **Question Answering** – Answer general knowledge and academic questions.
2. **Concept Explanation** – Explain complex topics in simple language.
3. **Quiz Generation** – Generate three MCQs with four options for a given passage.
4. **Summarization** – Convert long educational passages into concise summaries.
5. **Learning Recommendations** – Generate structured learning paths from beginner to advanced level.

## Backend Requirements
- Python 3.10+
- FastAPI framework
- Uvicorn ASGI server
- Jinja2 templating engine
- Google Gemini API

## Frontend Requirements
- HTML
- CSS
- Task selection dropdown
- Text input area
- Submit button
- Result display area

## AI Models
- Gemini 1.5 Pro via API for Q&A, summarization, quiz generation and learning paths.
- LaMini-Flan-T5-783M for concept explanation.

## Non-Functional Requirements
- Simple and accessible interface.
- Lightweight architecture.
- Responsive frontend.
- Clear and readable AI-generated responses.
- Error handling for invalid API responses.
