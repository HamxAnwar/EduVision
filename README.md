# Project: EduVision - An AI-Powered Interactive Learning Platform
## Core Focus for Starting:
### Interactive Learning Chatbot (LLM)
  A chatbot for answering questions and providing explanations for school/college-level subjects in Urdu and English. Example: "Explain Newton’s Laws of Motion" or "What is the capital of Balochistan?" Content will be curated for the local syllabus (e.g., Matric, FSC).

### Visual Learning Module (VLM)
- An image-based Q&A system for educational content.
- Example: Upload a diagram of the human body and ask, "What is this organ?"
- Focus on supporting science and geography topics initially.

### AI-Powered Quiz System (CV)
- A camera-based system to scan handwritten answers and grade simple quizzes.
- Start with MCQs and short answers for school students.

## Technical Stack:
Frontend:
- Streamlit.

Backend:
- Python (FastAPI) for API handling.
- Integration with GPT and CLIP models.

Database:
- SurrealDB for storing user interactions and content.

Computer Vision (CV):
- OpenCV or Tesseract for recognizing handwritten content.

## Milestones:
### Step 1:
- Build a basic chatbot answering questions from 2-3 school subjects.
- Collect feedback from teachers and students in your area.

### Step 2:
- Add image-based Q&A for one subject (e.g., Biology diagrams).
- Start testing the handwriting recognition system.

### Step 3:
- Combine the chatbot, visual Q&A, and grading system into one platform.

## Example Use Case (Starting):
Q: A student asks, "Explain the water cycle."
A: The chatbot provides a text-based explanation with a labeled diagram.

Q: A teacher uploads a biology diagram of the heart.
A: The system identifies the parts and explains them.

Q: A student submits handwritten answers to a math quiz.
A: The system grades simple questions like equations or short answers.

## Later to be done!
- Gather data on local schools' and colleges' needs.
- Identify key subjects and features that align with the Balochistan syllabus.
- Create a simple demo app and showcase it to schools/colleges for feedback.
