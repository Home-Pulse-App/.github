# 🏠🩺 Home Pulse

Welcome to the **Home Pulse**! This repository serves as the home for our full‑stack application and the shared standards, conventions, and resources that support it.

<p align="center">
  <img src="https://github.com/Home-Pulse-App/.github/raw/main/HomePulseLogo.png" alt="HomePulse Logo" width="300">
</p>

<p align="center">
  <img src="https://github.com/Home-Pulse-App/.github/raw/main/Home_Pulse_Demo.gif" alt=" Home Pulse Demo">
</p>

_This organization hosts the codebase and supporting materials for a modern full‑stack application. Our goal is to create a scalable, maintainable, and collaborative environment for development across backend, frontend, infrastructure, and documentation._

## 🚀 Overview

Home Pulse is a smart home platform that enables users to register their home, designate rooms, & connect smart home devices to monitor metrics such as temperature, humidity, & light status / intensity using ESP32-based devices.

## 📁 Repository Structure

This organization may contain multiple repositories. Typical structure:

- **Frontend** – Client‑side application
- **Backend** – Server‑side application and APIs
- **Infrastructure** – Deployment, IaC, config, CI/CD scripts
- **Design-docs** – Architecture diagrams, decision logs, specs

## 🧰 Tech Stack

While individual repositories specify their exact stack, the baseline technologies include:

- **Frontend:** React, Three.js, Tailwind CSS, React Three Fiber (Three.js for React), Sparkjs (for Gaussian Splat loading & utilities), shadCN, React Bits (component libraries), Chart.js / Vite
- **Backend:** Node.js / Express, MQTT, Swagger, JWT, BCRYPT, GridFS
- **Database:** Mongo DB
- **Infrastructure:** GitHub Actions

## 📨 Data flow

Device -->|MQTT Publish| Broker
Broker --> Backend
Backend --> DB[(MongoDB)]
Backend --> Frontend
Frontend -->|Fetch Data| Backend

## ✨ Development Standards

To maintain consistency across the organization, we follow these baseline guidelines:

### Code

- Use consistent code formatting (Prettier, ESLint)
- Favor clear, readable code over clever solutions
- Use TypeScript where possible

### Git

- Write clear commit messages, we use the conventional commit format enforced by commitizen
- Prefer feature‑branch workflow and pull requests

### Documentation

- Maintain an up‑to‑date README per repository
- Include setup steps, environment variables, and common workflows

## 🛠 Getting Started

Instructions vary by repository, but generally you can:

1. Clone the needed repositories
2. Install dependencies
3. Set environment variables as described in each repo
4. Run local development

## 🤝 Contribution Guidelines

Contributions are welcomed! Please:

- Open an issue before major changes
- Follow repository‑specific guidelines
- Keep discussions respectful and constructive

👥 Initial Contributors

This project was initially developed with contributions from:

- Alfredo Chavez Romero
- Adam Koep
- Artak Navoyan
- Miguel Angel Torrubia Moya

## 📄 Licensing

Each repository may specify its own license. If none is specified, please open an issue for clarification.

## 📬 Contact

For questions, ideas, or suggestions, open a discussion or issue in the appropriate repository.

Welcome aboard! 🎉
