# Quiz Backend

Simple backend for quiz app.

## Routes

GET /questions  
→ Returns all questions

POST /add-question  
→ Adds a new question

Example JSON:
{
  "question": "What is 2+2?",
  "options": ["2", "3", "4", "5"],
  "answer": "4"
}
