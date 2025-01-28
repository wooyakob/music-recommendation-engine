# Music Recommendation Engine

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Technologies](#technologies)
- [Getting Started](#getting-started)
- [License](#license)

---

## Overview
This project is my entry in Google's Gemini Long Context competition. 

Research is exploring how a long context window (1-2 million tokens), many-shot prompting, and in-context retrieval can improve model performance across a range of tasks using highly relevant and available data supplied during the initial input with context caching, versus other state-of-the-art external retrieval techniques like RAG, embeddings, and vector databases.

- Can Long-Context Language Models Subsume Retrieval, RAG, SQL, and More?
- Many-Shot In-Context Learning
- Gemini 1.5: Unlocking multimodal understanding across millions of tokens of context

This competition is looking for interesting use cases that could benefit from these unique features. I present mine in a notebook.

> This project is a notebook designed to show a use case that benefits from unique model features: long context windows, caching. It enables users to communicate naturally about their music taste, preferences, and to receive hyper-personalized recommendations and insights. The primary goal is to test out unique model features that enhance LLM performance from a user's perspective.

---

## Features
- Using datasets from BigQuery in Notebooks
- Using model caching to reduce token usage/cost
- Musical profiling and compatibility with other users

---

## Technologies
This project is built with:
- Python, SQL, Markdown
- Gemini API, Jupyter Notebooks

---

## Getting Started
Run cells in sequential order in a Jupyter Notebook, either locally or in Google Colab.

### Prerequisites
- Jupyter Notebook
- Gemini API Key
- Kaggle Dataset

---

## License
This project is licensed under the MIT License.
