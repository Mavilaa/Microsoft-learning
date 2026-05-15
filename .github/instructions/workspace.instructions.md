---
name: workspace
description: Workspace-level instructions for the SocOps Java project.
---

# Mandatory development checklist

- [ ] Run `cd socops && ./mvnw clean package`
- [ ] Run `cd socops && ./mvnw test`
- [ ] Start the app with `cd socops && ./mvnw spring-boot:run`
- [ ] Keep UI changes within Thymeleaf and `src/main/resources/static/css/app.css`

# Workspace summary

This repo is a Spring Boot game app in `socops` using Thymeleaf and custom CSS utilities.

Key files:
- `socops/src/main/java/com/socops/SocOpsApplication.java`
- `socops/src/main/java/com/socops/web/BingoRestController.java`
- `socops/src/main/java/com/socops/service/BoardAssembler.java`
- `socops/src/main/resources/templates/game.html`
- `socops/src/main/resources/static/css/app.css`

# Guidance

- Use the existing CSS utility system rather than adding new frameworks.
- Keep controller logic, game state, and template rendering aligned.
- Preserve the simple Spring Boot structure and avoid extra frontend build tooling.

# Notes

Workshop material lives under `workshop/` and describes setup, design, and multi-agent exercises for this project.
