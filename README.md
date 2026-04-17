# medical-multi-agent-docker
A multi-agent medical demo built with FastAPI, Docker Compose — featuring a triage agent and education agent coordinated via REST. For learning purposes only.

🏥 Medical Multi-Agent System — Docker Demo

A lightweight, containerized multi-agent application that simulates 
a medical consultation workflow.

🔧 How it works:
- Coordinator receives patient details (name, age, symptoms, question)
- Triage Agent classifies urgency: routine / urgent / emergency
- Education Agent provides basic health guidance
- All agents run as independent FastAPI microservices via Docker Compose

🛠️ Tech Stack: Python · FastAPI · Docker Compose · httpx · Pydantic

⚠️ Disclaimer: This is a demo/learning project only.
   It does NOT provide real medical advice.

📚 Built for: Big Data & AI coursework — exploring multi-agent 
   architecture patterns with containerized microservices.
