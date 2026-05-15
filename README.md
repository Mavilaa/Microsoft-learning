🌐 [Português (BR)](README.pt_BR.md) | [Español](README.es.md)

# Soc Ops

**A Social Bingo experience built as a hands-on GitHub Copilot Agent Lab.**

Meet new people, spark conversations, and win by matching questions with teammates in real life.

- 🎯 Designed for in-person mixers, workshops, and team icebreakers
- 🤖 Built with Java, Spring Boot, and agent-driven development
- 🚀 Includes guided lab content for setup, design, quiz generation, and multi-agent workflows

📚 **[Open the Lab Guide](workshop/GUIDE.md)**

---

## Why Soc Ops?

This repository is both a playable Social Bingo app and a learning lab for GitHub Copilot Agent Mode.

You can:

- build a small Java Spring Boot app with a polished UI
- explore frontend design and developer workflows
- use background and cloud agents to speed up docs, tests, and feature work
- learn how to turn project instructions into better AI outcomes

---

## What’s inside

- `socops/` – Spring Boot app, static frontend, REST controller, and game logic
- `workshop/` – guided walkthroughs for setup, design, quiz generation, and agent-led development
- `.github/agents/` – reusable agent definitions for TDD, design, and maintenance
- `.github/instructions/` – project-specific instructions that teach the AI about this repo

---

## Get started

### Run locally

```bash
cd socops
./mvnw spring-boot:run
```

Then visit `http://localhost:8080`.

### Build

```bash
cd socops
./mvnw clean package
```

### Test

```bash
cd socops
./mvnw test
```

---

## Lab roadmap

| Step | Focus |
|------|-------|
| [**00**](workshop/00-overview.md) | Overview & checklist |
| [**01**](workshop/01-setup.md) | Setup & context engineering |
| [**02**](workshop/02-design.md) | Design-first frontend |
| [**03**](workshop/03-quiz-master.md) | Custom Quiz Master |
| [**04**](workshop/04-multi-agent.md) | Multi-agent development |

> 📝 The workshop is also available offline in the `workshop/` folder.

---

## Notes

- This repo deploys automatically to GitHub Pages on push to `main`.
- Use `+` → **New cloud agent** in Copilot to explore async ideas like docs polish or design variations.
