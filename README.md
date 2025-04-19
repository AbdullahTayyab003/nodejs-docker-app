🐳 Node.js Docker App
A simple Node.js application containerized with Docker.

🚀 How to Run
1. Clone the Repository
git clone https://github.com/AbdullahTayyab003/nodejs-docker-app.git
cd nodejs-docker-app

2. Build the Docker Image
docker build -t nodejs-docker-app .

3. Run the Container
docker run -p 3000:3000 nodejs-docker-app

Then open http://localhost:3000 in your browser.

📁 Project Structure
nodejs-docker-app/
├── app.js
├── package.json
├── Dockerfile
└── README.md

📚 What I Learned
Basics of Node.js app structure

Writing a Dockerfile for Node.js

Building and running containers using Docker CLI

Mapping ports to access containerized apps in a browser

📌 Author
Abdullah Tayyab
https://github.com/AbdullahTayyab003