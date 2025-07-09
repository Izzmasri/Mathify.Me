# 🧠 Personalized Math Problem Rewriting Using AI

This project was built as part of the **Palestine Launchpad Hackathon**, organized by **Google** and **Stichting SPARK**. Our goal was to make math more engaging for students by **rewriting standard word problems** into **personalized themes** based on each student's interests — such as **football**, **Minecraft**, or **wildlife**. 🎮⚽🦁

## 🚀 What It Does

The system takes a traditional math word problem as input and, using **Retrieval-Augmented Generation (RAG)**, rewrites it to reflect the student’s interests without altering the underlying mathematical logic.

For example:
> Original: *"If John has 3 apples and buys 2 more, how many apples does he have now?"*

> Personalized (Minecraft Theme): *"If Steve mines 3 diamonds and then finds 2 more in a cave, how many diamonds does he have now?"*

## 🛠️ Tech Stack

- **FastAPI** – for building a lightweight, scalable API.
- **FAISS** – for fast similarity search over our curated thematic math dataset.
- **RAG (Retrieval-Augmented Generation)** – for combining prompt templates with retrieved samples to produce personalized problems.
- **Python** – core implementation language.

## 🧩 Features

- Input any standard word problem.
- Choose or detect a student interest (e.g., football, gaming, animals).
- Get a rewritten, themed version of the math problem.
- API-based architecture for integration into education platforms.

## 📦 Installation

```bash
git clone https://github.com/yourusername/personalized-math-ai.git
cd personalized-math-ai
pip install -r requirements.txt
uvicorn app.main:app --reload
