# Volleyball Player Management System

This project is a Django-based web application for managing volleyball players. It allows users to add, view, update, search, and delete player records through a simple interface.

## Features

- Add new players
- View the player list
- Search players by name
- Update player information
- Delete player records

## Technologies Used

- Python
- Django
- SQLite
- Docker

## Project Structure

- `players/` → app files, templates, views, models, and URLs
- `volleyhub/` → project settings and main configuration
- `Dockerfile` → Docker image instructions
- `requirements.txt` → project dependencies
- `manage.py` → Django management file

## Run Locally Without Docker

1. Install dependencies:

```bash
pip install -r requirements.txt
## Run With Docker

### Build the Docker Image
docker build -t volleyball-app .

### Run the Container
docker run -p 8000:8000 volleyball-app

Then open:
http://127.0.0.1:8000/


## Run Docker Image From GitHub

docker pull ghcr.io/sahyouinlynn-netizen/volleyball:latest

docker run -p 8000:8000 ghcr.io/sahyouinlynn-netizen/volleyball:latest
