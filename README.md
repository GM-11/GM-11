# Gopal Mathur

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/gopal-mathur-70044125a/)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:mathurgopal1001@gmail.com)

> I build production systems, not prototypes.  
> Backend · Distributed Systems · AI Infrastructure · Blockchain

Final-year Automotive Engineering undergrad at **DTU**, engineering software at the systems level — across C++, Go, Java, Rust, and Python. I own architecture, tradeoffs, and deployment. Not just code.

Currently interning at **Siemens Technology** building enterprise AI platforms, and serving as **President of WEB3DTU**.

---

## What I've Shipped

### Realtime Collaborative Document Editor
*C++ · Go · Java/Spring Boot · React · Kafka · PostgreSQL · Azure AKS*

Google Docs-style collaborative editor built from first principles across polyglot microservices.

- C++ OT engine with Lamport clock-based causal ordering, exposed via CGo FFI to Go
- Kafka event sourcing for async communication across 47,500+ ops under sustained load
- RS256 asymmetric JWT + JWKS-based stateless auth on the hot WebSocket path
- Deployed on Azure AKS with nginx ingress, cert-manager TLS, Azure Container Registry

**738 msgs/sec broadcast throughput · 400 concurrent ops/sec through the OT engine · 100% connection success across 105 concurrent users**

---

### Enterprise GenAI Content Automation Platform — Siemens
*Spring Boot · React · MongoDB · Azure CI/CD · RAG · Vector Embeddings*

Took a GenAI PoC to full production enterprise deployment across India, US, and Germany.

- Engineered RAG pipelines with vector embeddings for factual accuracy and domain consistency
- Implemented token-based rate limiting to control API cost exposure under multi-region concurrent load
- Owned the full lifecycle: architecture → compliance → containerized deployment via Docker + Azure CI/CD

**40% reduction in training content development time · Adopted as flagship AI initiative internally**

---

### Custom Decoder-only GPT
*PyTorch · Python · Transformer Architecture*

Implemented a GPT-style decoder Transformer from scratch — multi-head attention, positional embeddings, causal masking, full training pipeline with tiktoken.

- 6-layer Transformer (384-dim, 6 heads, 1024 FFN) trained for conversational text completion
- Built dataset loader and sequence batching for next-token prediction and perplexity evaluation

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
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
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
| SDE Intern | Siemens Technology & Services | May 2025 – Present |
| Smart Contract Engineer Intern | Digital Asset Network | Sep 2024 – Mar 2025 |
| Full Stack Developer | Ezinore Pvt. Ltd. | Feb 2023 – Sep 2023 |

---

## GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=GM-11&show_icons=true&theme=github_dark&hide_border=true&rank_icon=github" />
</p>

---

<p align="center">
  <sub>Open to Backend SDE · Full-Stack SDE · Systems/Infrastructure Engineer roles</sub>
</p>
