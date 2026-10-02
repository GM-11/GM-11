# Gopal Mathur

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/gopal-mathur-70044125a/)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:mathurgopal1001@gmail.com)

> Backend · Distributed Systems · AI Infrastructure

Software engineer working at the systems level across Go, Rust, C++, Java, and Python. B.Tech in Automotive Engineering from **DTU** (2026). I own architecture, tradeoffs, and deployment, not just the code.

Currently an **Implementation Engineer at Tennr**, a healthcare AI startup. Previously **SDE Intern at Siemens**, where I took a GenAI platform from PoC to production across three regions.

---

## What I've Shipped

### Realtime Collaborative Document Editor
*C++ · Go · Java/Spring Boot · React · Kafka · PostgreSQL · Azure AKS*

A Google Docs-style collaborative editor built from first principles across polyglot microservices.

- C++ operational transform (OT) engine with Lamport clock-based causal ordering, exposed to Go through CGo FFI
- Kafka event sourcing for async communication, tested across 47,500+ ops under sustained load
- RS256 asymmetric JWT with JWKS-based stateless auth on the hot WebSocket path
- Deployed on Azure AKS with nginx ingress, cert-manager TLS, and Azure Container Registry

**738 msgs/sec broadcast throughput · 400 concurrent ops/sec through the OT engine · 100% connection success across 105 concurrent users**

---

### Enterprise GenAI Content Automation Platform (Siemens)
*Spring Boot · React · MongoDB · Azure CI/CD · RAG · Vector Embeddings*

Took a GenAI PoC to a production enterprise deployment across India, the US, and Germany.

- Built RAG pipelines with vector embeddings to keep outputs factually accurate and consistent with the domain
- Added token-based rate limiting to cap API cost under concurrent multi-region load
- Owned the full lifecycle: architecture, compliance, and containerized deployment via Docker + Azure CI/CD

**40% reduction in training content development time · Adopted internally as a flagship AI initiative**

---

### Custom Decoder-only GPT
*PyTorch · Python · Transformer Architecture*

A GPT-style decoder Transformer implemented from scratch: multi-head attention, positional embeddings, causal masking, and a full training pipeline using tiktoken.

- 6-layer Transformer (384-dim, 6 heads, 1024 FFN) trained for conversational text completion
- Custom dataset loader and sequence batching for next-token prediction and perplexity evaluation

---

## Skills

**Languages**

![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)

**Backend / Infrastructure**

![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![gRPC](https://img.shields.io/badge/gRPC-244C5A?style=flat-square&logo=grpc&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)

**AI / ML**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)

**Blockchain**

![Solana](https://img.shields.io/badge/Solana-4E44CE?style=flat-square&logo=solana&logoColor=white)
![Ethereum](https://img.shields.io/badge/Ethereum-3C3C3D?style=flat-square&logo=ethereum&logoColor=white)

---

## Experience

| Role | Company | Period |
|---|---|---|
| Implementation Engineer | Tennr | Aug 2026 – Present |
| SDE Intern | Siemens Technology & Services | May 2025 – May 2026 |
| Smart Contract Engineer Intern | Digital Asset Network | Sep 2024 – Mar 2025 |
| Full Stack Developer | Ezinore Pvt. Ltd. | Feb 2023 – Sep 2023 |

---

## GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=GM-11&show_icons=true&theme=github_dark&hide_border=true&rank_icon=github" />
</p>

---

<p align="center">
  <sub>Open to Backend SDE · Distributed Systems · Systems/Infrastructure Engineer roles</sub>
</p>
