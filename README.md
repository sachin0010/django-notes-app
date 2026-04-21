# Simple Notes App for TWS Community
This is a simple notes app built with React and Django.
<img width="1917" height="906" alt="image" src="https://github.com/user-attachments/assets/935e7d7e-8aea-4ebc-8837-f14b4077f077" />


## Requirements
1. Python 3.9
2. Node.js
3. React

## Installation
1. Clone the repository
```
git clone https://github.com/LondheShubham153/django-notes-app.git
```

2. Build the app
```
docker build -t notes-app .
```

3. Run the app
```
docker run -d -p 8000:8000 notes-app:latest
```

## Nginx

Install Nginx reverse proxy to make this application available

`sudo apt-get update`
`sudo apt install nginx`
