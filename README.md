# Study Buddy Agent 🤖📚

An AI-powered study assistant that helps students learn smarter, not harder.

## Problem

As a student, I found that:
- Reading 50-page lecture PDFs takes too long to extract key points
- Cramming before exams leads to poor retention
- Generic AI chatbots don't understand my course-specific content

## Solution

A multi-step agent workflow:

1. **Ingest Agent** — Upload lecture PDFs, extract text and structure
2. **Distill Agent** — Generate flashcards (Q&A pairs) from key concepts
3. **Schedule Agent** — Plan review sessions using spaced repetition algorithm
4. **Tutor Agent** — Answer questions using RAG (Retrieval-Augmented Generation) on your own course materials

## Tech Stack

- Python + LangChain
- OpenAI GPT-4o / Claude API
- ChromaDB for vector storage
- Streamlit for simple UI

## Results

- Used for 3 courses this semester (Data Structures, OS, Machine Learning)
- Reduced review prep time from 3 hours to 20 minutes per chapter
- Final exam scores improved by ~15% compared to last semester

## Run Locally

```bash
pip install -r requirements.txt
streamlit run app.py
