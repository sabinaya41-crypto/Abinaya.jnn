# 06. Project Testing

## Testing Objective
The purpose of testing is to verify that the major EduGenie functions can accept user input and return the intended type of educational output.

## Functional Test Checklist

| Test | Feature | Test Input | Expected Function |
|---|---|---|---|
| T01 | Q&A | An academic question | AI-generated answer |
| T02 | Explanation | A complex topic | Simplified explanation |
| T03 | Quiz | Educational passage | Three MCQs with four options |
| T04 | Summary | Long paragraph | Concise summary |
| T05 | Learning Path | Topic name | Beginner-to-advanced learning guidance |

## Testing Areas
- Frontend form submission
- FastAPI endpoint connection
- AI module response
- Quiz JSON parsing
- Error handling
- Display of generated results

## Error Handling
The project includes handling for errors during AI generation or quiz-response parsing and can return a useful error message for debugging.

## Note
The project document describes functional testing activities, but it does not provide a complete pass/fail test report with recorded test values. The table above is therefore a structured testing checklist based on the documented features.
