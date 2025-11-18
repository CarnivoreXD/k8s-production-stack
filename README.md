# Docker to Kubernetes Migration Journey

## Overview
This project began from Docker’s official “getting-started” example, which I plan to extended into a production-style Kubernetes deployment to practice container orchestration, CI/CD, and SRE workflows over time.

## Project Progress

### Phase 1: Docker Fundamentals 
- Containerized Node.js application
- Optimized Dockerfile with multi-stage builds
- Docker Compose for local development
- Volume management for data persistence

### Phase 2: Kubernetes Migration (In Progress)
- [ ] Kubernetes manifests (Deployment, Service, ConfigMap)
- [ ] Horizontal Pod Autoscaler configuration
- [ ] Ingress controller setup
- [ ] Persistent Volume Claims for stateful data

### Phase 3: Production Readiness (Planned)
- [ ] Prometheus & Grafana monitoring
- [ ] Helm chart packaging
- [ ] GitOps with ArgoCD
- [ ] Chaos engineering tests

## Technologies & Skills Used
- **Containerization:** Docker, Docker Compose, Multi-stage builds
- **Orchestration:** Kubernetes, kubectl, Minikube
- **CI/CD:** GitHub Actions, Automated testing
- **Monitoring:** Prometheus, Grafana (coming soon)
- **IaC:** Terraform, Helm (coming soon)

## Learning Objectives
This project helped me understand:
- Container orchestration patterns
- Service mesh concepts
- Cloud-native best practices
- 12-factor application principles