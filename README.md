# Express Docker App

A simple Node.js Express application containerized with Docker, designed for CI/CD workshops.

## Features

- RESTful API with Express.js
- Dockerized for easy deployment
- Ready for CI/CD integration (e.g., Jenkins)

## Prerequisites

- [Node.js](https://nodejs.org/)
- [Docker](https://www.docker.com/)

## Getting Started

### Clone the repository

```bash
git clone https://github.com/your-username/express-docker-app.git
cd express-docker-app
```

### Install dependencies

```bash
npm install
```

### Run locally

```bash
npm start
```

### Build and run with Docker

```bash
docker build -t express-docker-app .
docker run -p 3000:3000 express-docker-app
```

## Project Structure

```
.
├── Dockerfile
├── package.json
├── src/
│   └── index.js
└── README.md
```

## License

MIT