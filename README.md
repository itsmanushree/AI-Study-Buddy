# 🎓 AI Study Buddy

An AI-powered study assistant built using **Google Gemini API, Python, and Google Colab**.

This project demonstrates how an AI agent can understand a student's request and choose the appropriate tool to help them study.

## 🚀 What Can It Do?

The Study Buddy has three tools:

- 📖 **Explain Concept** — explains a topic for beginners
- ❓ **Generate Quiz** — creates a short quiz on a topic
- 📝 **Revision Notes** — creates concise revision notes

The agent can also remember recent conversation context, so you can say things like:

> "Teach me OOP."

and then:

> "Quiz me on it."

## 🧠 How It Works

```text
Student Request
       ↓
   Gemini Agent
       ↓
 Chooses a Tool
       ↓
Python Executes Tool
       ↓
    Response
