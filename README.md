# NetByte Core

**NetByte Core** is the orchestration and intelligence layer of the NetByte SDI (Sovereign Digital Infrastructure) platform — a full-stack, self-contained, AI-native infrastructure system built for government, enterprise, and regulated environments.

This repository will serve as the central reference point for infrastructure orchestration, network policy, identity integration, and AI automation logic that powers SDI-Core deployments.

---

## 🌐 What is NetByte Core?

NetByte Core is the brain of the NetByte platform. It manages:

- Secure orchestration of **Zone devices** across distributed environments
- Cryptographically verified CI/CD pipelines using Gitea
- Identity issuance and post-quantum authentication using Kyber + Blake3
- Real-time SD-WAN routing, threat intelligence, and AI-driven automation
- Distributed storage, SIEM, deep packet capture, and zero-trust policy enforcement

---

## 🧱 Platform Stack

Core components integrated at launch:

- [MinIO](https://min.io) – Encrypted object storage
- [Wazuh](https://wazuh.com) – SIEM and endpoint threat detection
- [Arkime](https://arkime.com) – Full packet capture and search
- [Netmaker](https://netmaker.io) – Mesh SD-WAN tunneling via WireGuard
- [Gitea](https://gitea.io) – Cryptographic source + pipeline control
- [Weaviate](https://weaviate.io) + Mixtral – RAG for threat/action intelligence

---

## 🔐 Identity + Auth

- All users are issued decentralized, device-bound IDs via **Kyber-based certs**
- Certs are hashed using **Blake3**, embedded into QR codes, and stored locally
- Supports biometric MFA, self-verifying identity sessions, and audit-traceable access control

---

## 📦 Roadmap

This repo will eventually include:

- Ansible/Terraform provisioning scripts
- Hardened container images
- AI policy engine logic
- Real-time API telemetry and graph views
- CI/CD integration with on-device Gitea

---

## 🚧 Status

This repository is currently **in early development** and is not yet production-ready. Contributions are not yet open. Final architecture, licensing, and documentation will be published once initial deployments are complete.

---

## 📫 Contact

For platform inquiries, partnerships, or enterprise deployments, contact:

**Chris McWhorter**  
Founder & Principal Architect  
📧 chris@netbyte.ai  
🌐 [https://netbyte.ai](https://netbyte.ai)
