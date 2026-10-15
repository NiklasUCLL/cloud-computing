Kilroy was here

# Storingsmelder

Een klein meldingensysteem voor storingen. Je meldt een storing via een
formulier, je ziet de openstaande meldingen in een lijst, en je sluit ze af als
ze opgelost zijn.

Deze applicatie is het startpunt voor **Cloud computing (B-UCLL-MGN13A)**.

---

## Requirements

- Docker
- Docker Compose
- Git

## Installation
### 1. Clone repo
Run `git clone https://github.com/NiklasUCLL/cloud-computing && cd cloud-computing && cp .env.example .env`
### 2. Setting up environment variables
Edit your .env file and set the following:
- `DATABASE_URL`: replace the `<>` with the the chosen username, password and database name
- `POSTGRES_USER`: replace the `<>` with the the chosen username
- `POSTGRES_PASSWORD`: replace the `<>` with the the chosen password
- `POSTGRES_DB`: replace the `<>` with the the chosen database name
### 3. Starting the containers
Run `docker compose up`
### 4. Opening the webinterface
Open `http://127.0.0.1:8000`
