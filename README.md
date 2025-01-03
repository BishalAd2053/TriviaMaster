# TriviaMaster

TriviaMaster is a microservices-based trivia game platform inspired by *Are You Smarter Than a 5th Grader?*. It uses dynamic question generation powered by OpenAI and follows a scalable architecture.

## Features
- Dynamic trivia question generation based on grade levels.
- Tracks player profiles, scores, and game history.
- Fully modular microservices architecture.
- RESTful API for seamless integration.
- Optional real-time notifications.

## Technology Stack
- **Backend:** Spring Boot, OpenAI API, Redis, PostgreSQL
- **Frontend:** React.js
- **Communication:** REST, gRPC (internal)
- **Deployment:** Docker, Kubernetes
- **Monitoring:** ELK Stack or Prometheus/Grafana

## Microservices
1. **API Gateway**: Handles routing, security, and load balancing.
2. **Question Service**: Generates trivia questions using OpenAI.
3. **Game Logic Service**: Manages game rules and state.
4. **Player Service**: Tracks player data and scores.
5. **Frontend**: Provides a web interface or Alexa integration.

---

## Getting Started

### Prerequisites
- JDK 17+
- Node.js 16+
- Docker and Docker Compose
- OpenAI API Key
- PostgreSQL and Redis

### Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/TriviaMaster.git
   cd TriviaMaster
