# GitHub Copilot Instructions

This repository is a Spring Boot application with a simple Thymeleaf-based game UI.
Keep changes lightweight and aligned with the existing service, template, and CSS utility patterns.

## Design Guide

- Use the existing CSS utilities in `socops/src/main/resources/static/css/app.css` whenever possible.
- Favor semantic, composable layouts rather than adding new frontend frameworks.
- Design for a polished dark theme with strong contrast, subtle glows, and layered surfaces.
- Preserve the HTML-first approach by styling the Thymeleaf page directly, not by introducing a separate frontend build.
- Keep interactions simple: clear buttons, readable tile text, and a visible victory state.

## Development Notes

- Start the app with `cd socops && ./mvnw spring-boot:run`.
- Build with `cd socops && ./mvnw clean package`.
- Test with `cd socops && ./mvnw test`.
