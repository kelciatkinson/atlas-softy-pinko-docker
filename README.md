# 🐳 Atlas Softy Pinko Docker

A production-style multi-container application built with Docker —
featuring load balancing, reverse proxy, horizontal scaling, 
and full-stack service orchestration.

## 🏗️ Architecture
[Client Request]

 ↓

[Reverse Proxy / Load Balancer]

↓         ↓

[API Server 1] [API Server 2]  ← Round-robin load balancing

↓

[Front-End Nginx Server]


## 🚀 Key Features
- 🔄 Round-robin load balancing across scaled API instances
- 🐍 Python/Flask backend containerized with pip dependency management
- 🌐 Nginx front-end serving static content with dynamic backend data
- 📦 Docker Compose orchestration for full multi-service automation
- 📈 Horizontal scaling with multiple API server instances

## 🛠️ Tech Stack
Docker · Docker Compose · Python · Flask · 
Nginx · JavaScript · Ubuntu

## 💡 AI & Automation Relevance
Multi-container orchestration and automated service scaling 
mirror the infrastructure patterns used in deploying AI 
microservices, automation pipelines, and integrated tool 
ecosystems.
