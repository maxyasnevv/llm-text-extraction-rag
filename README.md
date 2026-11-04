# llm-text-extraction-rag
Applying LLMs for information extraction and text analysis using RAG and AI agents.
# Применение LLM для извлечения информации и анализа текстов (RAG, LLM-агенты)

## Описание проекта
Проект посвящен разработке сервиса для интеллектуального анализа документов и извлечения информации с использованием подходов Retrieval-Augmented Generation (RAG) и LLM-агентов. 

Сервис предоставляет интерфейс (Telegram-бот / Web UI) для ответов на вопросы пользователя по динамически загружаемому пулу неструктурированных документов с возможностью выбора языковой модели и метода извлечения контекста.

## Стек технологий
* **Язык разработки:** Python 3.11+
* **Управление зависимостями:** Poetry
* **Контейнеризация и оркестрация:** Docker, Docker Compose
* **Контроль качества кода (Code Style):** Pre-commit, Black, isort, Flake8, Pylint
* **LLM & RAG фреймворки:** LangChain / LangGraph, LlamaIndex
* **Интерфейс:** Telegram Bot (Aiogram 3) / Gradio / Streamlit *(в процессе реализации)*

---

## Архитектура и методы RAG
Планируется исследование и реализация нескольких подходов к извлечению информации:
- [ ] Базовый векторный поиск (Naive RAG)
- [ ] Contextual Retrieval / Hybrid Search
- [ ] Self-RAG / Corrective RAG (CRAG)
- [ ] Graph RAG (извлечение сущностей и связей)

---

## Установка и запуск

### 1. Клонирование репозитория
```bash
git clone [https://github.com/](https://github.com/)maxyasnevv/llm-text-extraction-rag.git
cd llm-text-extraction-rag
