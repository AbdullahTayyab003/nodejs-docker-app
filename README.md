# Node.js Docker App 🚀

A simple Node.js application containerized using Docker — perfect for learning the basics of Docker and Node.js integration.

## 🔧 Tech Stack

- Node.js
- Express.js
- Docker

## 📦 How to Run

### 1. Clone the repository

```bash
git clone https://github.com/AbdullahTayyab003/nodejs-docker-app.git
cd nodejs-docker-app

2. Build Docker Image

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
. Creating a basic Node.js server

. Writing a Dockerfile

. Building and running Docker containers