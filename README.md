# cc-lab-3

- SRN : PES2UG23CS086
- NAME : APHARNA KAMATH R
- SECTION : B

This project is a Flask-based spam detection web application using a trained
machine learning model. The application is containerized using Docker to ensure
portability and easy deployment.

## Technologies used : 

- Python
- Flask
- Scikit-learn
- Docker

## How to Build & Run :

#### Build Docker Image
docker build -t spam-web-app .

#### Run Docker Container
docker run -p 5000:5000 spam-web-app

## Output
Open browser and visit:
http://localhost:5000
