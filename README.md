# Hey, I'm Pushp Hans 👋

**Flutter & Agentic AI Engineer** — I build mobile products and production-grade agentic AI systems.

---

### 🤖 What I've Built

- **Production Multi-Agent System** — Conversational agent with persistent chat history + a subagent that dynamically generates DB queries to surface data on the frontend (LangGraph + FastAPI + PostgreSQL)
- **Flutter Applications** — 1 year production experience, end-to-end ownership from architecture to Play Store & App Store deployment
- **LLM-powered backends** — FastAPI microservices wrapping LangChain/LangGraph agents, ready for real-world use

---

### 🛠 Stack

**AI & Agents** → LangGraph • LangChain • FastAPI • Python • LLM Integration • PostgreSQL • Redis • Docker

**Mobile** → Flutter • Dart • State Management • Clean Architecture

---

### 📂 Projects

| Project | Stack | What it does |
|---|---|---|
| Multi-Agent System | LangGraph + FastAPI + PostgreSQL | Chat agent with memory + DB query subagent |
| Flutter + AI App | Flutter + FastAPI | Mobile app on top of AI backend |
| RAG Pipeline *(WIP)* | LangChain + Vector DB | Retrieval-Augmented Generation |

---

### 📬 Let's Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-pushphans1502-blue?style=flat&logo=linkedin)](https://linkedin.com/in/pushphans1502)
[![Email](https://img.shields.io/badge/Gmail-pushp.hans1502-red?style=flat&logo=gmail)](mailto:pushp.hans1502@gmail.com)

*Open to roles at funded startups & product companies — Flutter, Applied AI, or both.*



- uses: Platane/snk@v3
  with:
    # github user name to read the contribution graph from (**required**)
    # using action context var `github.repository_owner` or specified user
    github_user_name: ${{ github.repository_owner }}

    # list of files to generate.
    # one file per line. Each output can be customized with options as query string.
    #
    #  supported options:
    #  - palette:           A preset of color, one of [github, github-dark, github-light]
    #  - color_snake:       Color of the snake
    #  - color_dots:        Coma separated list of dots color.
    #                       The first one is 0 contribution, then it goes from the low contribution to the highest.
    #                       Exactly 5 colors are expected.
    #  - color_background:  Color of the background (for gif only)
    outputs: |
      dist/github-snake.svg
      dist/github-snake-dark.svg?palette=github-dark
      dist/ocean.gif?color_snake=orange&color_dots=#bfd6f6,#8dbdff,#64a1f4,#4b91f1,#3c7dd9&color_background=#aaaaaa
