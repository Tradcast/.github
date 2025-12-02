# Tradcast: Farcaster-Native Trading simulation Miniapp

Welcome to Tradcast, a Farcaster-native trading miniapp built to simulate real high-volatility markets — without risking real money.
Turn your free time into real trading experience, backed by a robust, scalable, and event-driven architecture.

---

### 🚀 Features

- Live Volatile Market Prices: Simulate real market conditions using real-time feeds.
- Zero-Risk Training: Practice trading with no financial loss.
- Farcaster Miniapp UX: Seamless interaction directly inside Farcaster clients.
- Gamified System: Stats, history, streaks, achievements.
- Microservices Architecture: Fast, scalable, fault-tolerant.

--- 

### 🧱 Tech Stack

##### Miniapp & Frontend

- Farcaster Miniapp Framework
- Next.js 14 (App Router)
- TypeScript
- Lightweight-Charts (Trading UI)
- TailwindCSS

##### Backend & Services

- FastAPI (main backend service)
- Python with async workers
- Node.js for supporting services

##### Data & Messaging

- Firestore (primary database)
- Redis (caching + rate limiting)
- RabbitMQ (message broker for trade events)
- MongoDB (historical logs / analytics pipelines)

##### Infrastructure

- Docker / Docker Compose
- Load Balancer (Nginx)
- Scalable Microservice Clusters
- Monitoring & Logging stacks

##### Smart Contracts 
- Hardhat
- EVM-compatible test networks
