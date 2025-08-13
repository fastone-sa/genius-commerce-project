# Genius Commerce - The Performance Commerce Platform

## 1. Project Description

Genius Commerce is a next-generation e-commerce platform designed to empower merchants with AI-driven marketing tools. It integrates a powerful advertising engine ("Smart Marketing") directly into the e-commerce workflow, allowing sellers to create, manage, and analyze high-performance ad campaigns seamlessly. For shoppers, it offers a highly personalized and intelligent shopping experience.

## 2. Technology Stack

- **Backend:** Node.js, NestJS, TypeScript, PostgreSQL, Redis, Elasticsearch
- **Frontend:** Next.js, React, TypeScript, Tailwind CSS
- **AI/ML:** Python, TensorFlow/PyTorch (as a separate service)
- **Infrastructure:** Docker, Kubernetes, AWS (planned)
- **Testing:** Jest (Unit/Integration), Cypress (End-to-End)

## 3. Running the Project Locally

1.  **Clone the repository.**
2.  **Create environment files:** Copy `.env.example` in each service to `.env` and fill in the variables.
3.  **Build and run the services using Docker Compose:** `docker-compose up --build`
