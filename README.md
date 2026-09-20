# Gorin 五輪

> Self-hosted, gamified fitness, nutrition and habit tracker inspired by *The Book of Five Rings*.

**Status: 🚧 in active development (MVP in progress).**

Gorin turns your real data (workouts, meals, steps and daily habits) into levels, ranks and daily quests. The goal is balance: your rank is only as strong as your weakest pillar.

## Features

- 🏋️ Custom exercises, routines and workout sessions (gym, cardio, martial arts, anything)
- 🍽️ Meal logging with calories and macros, manual foods and barcode lookup (Open Food Facts)
- 👟 Steps tracking (manual on web, phone sensor on the mobile app)
- 🧠 Custom habits (coding, studying, reading...) grouped in pillars
- 🎮 XP, levels, daily quests and ranks (E to S) computed from your real data
- 👥 Multi-user server (first user is the admin), optional rankings
- 📤 Full data export (JSON / CSV)
- 🌍 English and Spanish
- 🤖 *Planned:* bring-your-own-key AI assistant (Gemini, OpenAI, Anthropic, local models)
- 📱 *Planned:* offline-first Android app with sync

## The five pillars

Earth (strength) · Water (endurance) · Fire (nutrition) · Wind (versatility) · Void (mind and discipline). Pillars are customizable per user.

## Tech stack

| Area | Technology |
|---|---|
| Backend | Java 21, Spring Boot 3, Spring Security (JWT), Spring Data JPA |
| Database | PostgreSQL, Flyway migrations |
| Frontend | Angular |
| API docs | OpenAPI / Swagger |
| Testing | JUnit 5, Mockito, Testcontainers |
| DevOps | Docker Compose, GitHub Actions |

## Quick start

Coming soon: `docker compose up` will start the API, database and web app.

## Documentation

- [Architecture and design decisions](docs/ARCHITECTURE.md)
- [Roadmap](docs/ROADMAP.md)

## Roadmap

- [ ] Auth, users and admin
- [ ] Exercises, routines and sessions
- [ ] Foods and meals
- [ ] Habits, steps and body weight
- [ ] XP, levels and daily quests
- [ ] Data export
- [ ] Angular web app
- [ ] Docker, CI and deployment
- [ ] Rank standards (by sex, age and body weight)
- [ ] AI assistant (BYOK)
- [ ] Sync and offline mobile app

## Disclaimer

Gorin is a personal project and not medical advice. Rankings and any AI-generated suggestions are informative only, and you are responsible for your own training and nutrition.

## License

[MIT](LICENSE)
