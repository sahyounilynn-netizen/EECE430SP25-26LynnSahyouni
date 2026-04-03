# Volleyball Player Management System

This project is a Django-based web application for managing volleyball players.

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

- players/
- volleyhub/
- Dockerfile
- requirements.txt
- manage.py

## Run Locally Without Docker

pip install -r requirements.txt  
python manage.py migrate  
python manage.py runserver  

Open: http://127.0.0.1:8000/

---

## Run With Docker

docker build -t volleyball-app .  
docker run -p 8000:8000 volleyball-app  

Open: http://127.0.0.1:8000/

---

## Run Docker Image From GitHub

docker pull ghcr.io/sahyounilynn-netizen/volleyball:latest  
docker run -p 8000:8000 ghcr.io/sahyounilynn-netizen/volleyball:latest  

Open: http://127.0.0.1:8000/
