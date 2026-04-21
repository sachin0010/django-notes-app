# Simple Notes App for TWS Community
This is a simple notes app built with React and Django.
<img width="1910" height="445" alt="image" src="https://github.com/user-attachments/assets/d0c0a011-3d4b-419b-a40d-2e884955d1d4" />



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
