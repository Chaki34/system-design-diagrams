# 🚀 System Design Diagrams

<p align="center">
  <img src="https://img.shields.io/badge/System%20Design-Architecture-blueviolet?style=for-the-badge&logo=diagrams.net" />
  <img src="https://img.shields.io/badge/Distributed-Systems-orange?style=for-the-badge&logo=icloud" />
  <img src="https://img.shields.io/badge/Microservices-Architecture-blue?style=for-the-badge&logo=microservices" />
</p>

<p align="center">
  <strong>🎨 A visual collection of system design concepts, software architectures, distributed systems, and scalable solutions.</strong>
</p>

<p align="center">
  <a href="https://github.com/Chaki34/system-design-diagrams">
    <img src="https://img.shields.io/github/stars/Chaki34/system-design-diagrams?style=for-the-badge&logo=github&label=Stars" />
  </a>
  <a href="https://github.com/Chaki34/system-design-diagrams">
    <img src="https://img.shields.io/github/forks/Chaki34/system-design-diagrams?style=for-the-badge&logo=github&label=Forks" />
  </a>
  <img src="https://img.shields.io/badge/Diagrams-SVG-success?style=for-the-badge&logo=svg" />
  <img src="https://img.shields.io/badge/Learning-System%20Design-ff69b4?style=for-the-badge" />
</p>

---

<h2 align="center">🧠 Visualize → Understand → Design → Scale</h2>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&height=120&section=header&text=SYSTEM%20DESIGN&fontSize=40&fontAlignY=35&animation=twinkling" />
</p>

Welcome to **System Design Diagrams** — a continuously growing collection of **architecture diagrams, system workflows, database designs, scalability patterns, distributed-system concepts, and production architecture**.

This repository is focused on **visual learning**.

Instead of understanding system design only through long explanations, these diagrams help visualize how:

```text
👤 Client
   ↓
🌐 API
   ↓
⚡ Services
   ↓
🚀 Cache / Queue
   ↓
🗄️ Database
   ↓
☁️ Storage
```

components communicate, scale, store data, and handle failures.

---

## 🌟 What's Inside?

<table>
<tr>
<td align="center" width="25%">

### 🏗️

**System Architecture**

</td>
<td align="center" width="25%">

### ⚙️

**Microservices**

</td>
<td align="center" width="25%">

### 🗄️

**Database Design**

</td>
<td align="center" width="25%">

### 📈

**Scalability**

</td>
</tr>

<tr>
<td align="center">

### 🔄

**Data Flow**

</td>
<td align="center">

### ⚡

**Caching**

</td>
<td align="center">

### 📨

**Message Queues**

</td>
<td align="center">

### 🔐

**Security**

</td>
</tr>

<tr>
<td align="center">

### ☁️

**Cloud Architecture**

</td>
<td align="center">

### 🛡️

**Fault Tolerance**

</td>
<td align="center">

### 🌐

**Distributed Systems**

</td>
<td align="center">

### 🚦

**Load Balancing**

</td>
</tr>
</table>

---

# 🚀 Featured System Designs

## 🔗 Advanced URL Shortener

<p align="center">
  <img src="https://img.shields.io/badge/Architecture-Advanced-purple?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Scalability-High-red?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Availability-High-success?style=for-the-badge" />
</p>

A production-oriented system design for building a **highly scalable URL-shortening service**.

### ⚡ Key Components

| Component           | Purpose                         |
| ------------------- | ------------------------------- |
| 🌐 API Gateway      | Entry point for client requests |
| ⚖️ Load Balancer    | Distributes traffic             |
| 🆔 ID Generator     | Generates unique short URLs     |
| ⚡ Redis Cache       | Low-latency URL lookup          |
| 🗄️ Database        | Persistent URL storage          |
| 🔀 Sharding         | Horizontal database scaling     |
| 🔁 Replication      | High availability               |
| 🚦 Rate Limiter     | Prevents API abuse              |
| 📊 Analytics        | Tracks URL usage                |
| 🛡️ Fault Tolerance | Handles service failures        |

📁 **Explore:** [`url-shortener/`](./url-shortener/)

---

# 🏛️ Architecture at a Glance

<p align="center">

```text
                         👤 CLIENTS
                              │
                              ▼
                    ┌──────────────────┐
                    │   🌐 API GATEWAY │
                    └────────┬─────────┘
                             │
                    ┌────────▼─────────┐
                    │ ⚖️ LOAD BALANCER │
                    └────────┬─────────┘
                             │
             ┌───────────────┼───────────────┐
             ▼               ▼               ▼
       ┌──────────┐    ┌──────────┐    ┌──────────┐
       │ Service A│    │ Service B│    │ Service C│
       └─────┬────┘    └─────┬────┘    └─────┬────┘
             │               │               │
             └───────────────┼───────────────┘
                             ▼
                      ┌─────────────┐
                      │ ⚡ CACHE     │
                      └──────┬──────┘
                             │
                             ▼
                      ┌─────────────┐
                      │ 🗄️ DATABASE │
                      └──────┬──────┘
                             │
                             ▼
                      ☁️ STORAGE
```

</p>

---

# 🎨 Visual Learning

The repository uses **SVG diagrams** as the primary format.

### Why SVG?

<table>
<tr>
<td>🔍</td>
<td><strong>Scalable</strong><br/>Zoom without losing quality.</td>

<td>🎨</td>
<td><strong>Visual</strong><br/>Clean architecture representation.</td>
</tr>

<tr>
<td>📐</td>
<td><strong>Precise</strong><br/>Perfect for technical diagrams.</td>

<td>⚡</td>
<td><strong>Lightweight</strong><br/>Efficient compared with large raster images.</td>
</tr>
</table>

---

# 📂 Repository Structure

```text
system-design-diagrams/
│
├── 📄 README.md
│
├── 🔗 url-shortener/
│   ├── 🏗️ architecture.svg
│   ├── 🗄️ database-design.svg
│   ├── 🔄 request-flow.svg
│   ├── ⚡ caching.svg
│   ├── 🔀 sharding.svg
│   └── 📊 analytics.svg
│
├── ⚙️ microservices/
│   ├── api-gateway.svg
│   ├── service-discovery.svg
│   ├── service-communication.svg
│   └── event-driven.svg
│
├── 🗄️ databases/
│   ├── replication.svg
│   ├── sharding.svg
│   ├── indexing.svg
│   └── partitioning.svg
│
└── 📈 scalability/
    ├── load-balancing.svg
    ├── caching.svg
    ├── horizontal-scaling.svg
    └── vertical-scaling.svg
```

---

# 🧠 Core System Design Concepts

<div align="center">

| 🌐 Distributed Systems | 🗄️ Databases | ⚡ Performance  |
| ---------------------- | ------------- | -------------- |
| CAP Theorem            | Sharding      | Caching        |
| Consistent Hashing     | Replication   | CDN            |
| Consensus              | Indexing      | Load Balancing |
| Fault Tolerance        | Partitioning  | Rate Limiting  |

| ⚙️ Architecture   | 📨 Communication | 🛡️ Reliability   |
| ----------------- | ---------------- | ----------------- |
| Microservices     | Kafka            | High Availability |
| API Gateway       | Message Queues   | Fault Tolerance   |
| Service Discovery | Event Driven     | Disaster Recovery |
| Serverless        | Pub/Sub          | Observability     |

</div>

---

# 🗺️ System Design Learning Roadmap

<p align="center">

```text
                    🧠 SYSTEM DESIGN
                           │
             ┌─────────────┴─────────────┐
             ▼                           ▼
       📚 FUNDAMENTALS              🏗️ ARCHITECTURE
             │                           │
             ▼                           ▼
       🌐 NETWORKING                ⚙️ MICROSERVICES
             │                           │
             └─────────────┬─────────────┘
                           ▼
                    🗄️ DATABASES
                           │
                           ▼
                       ⚡ CACHE
                           │
                           ▼
                     📨 MESSAGING
                           │
                           ▼
                     📈 SCALABILITY
                           │
                           ▼
                  🌐 DISTRIBUTED SYSTEMS
                           │
                           ▼
                  ☁️ PRODUCTION SYSTEMS
```

</p>

---

# 🔥 What I'm Exploring

* 🌐 Distributed Systems
* 🏗️ Large-Scale Architecture
* ⚙️ Microservices
* 🗄️ SQL & NoSQL Databases
* 🔀 Database Sharding
* 🔁 Database Replication
* ⚡ Distributed Caching
* 📨 Kafka & Message Queues
* 🚦 Rate Limiting
* ⚖️ Load Balancing
* 🔐 Authentication & Authorization
* 🛡️ Fault Tolerance
* 📈 Horizontal Scaling
* ☁️ Cloud Architecture
* 🔎 Observability
* 🔄 Distributed Transactions
* 🧩 Event-Driven Architecture

---

# 🤝 Contributions

Found an issue in a diagram?

Have an interesting system design to contribute?

You're welcome to:

```text
🐛 Report an issue
        ↓
💡 Suggest an improvement
        ↓
🔧 Create a Pull Request
        ↓
🚀 Improve the collection
```

---

# ⭐ Support

If you find these diagrams useful for learning **System Design, Software Architecture, Microservices, or Distributed Systems**, consider giving the repository a ⭐.

<p align="center">

### ⭐ Star the repository if you find it useful!

</p>

---

# 👨‍💻 Author

<p align="center">

<img src="https://img.shields.io/badge/Created%20by-Debmalya%20Chaki-blueviolet?style=for-the-badge&logo=github" />

</p>

<p align="center">

**Learning • Designing • Visualizing • Scaling**

</p>

---

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&height=100&section=footer" />
</p>

<h3 align="center">

🚀 Design It • 🎨 Visualize It • 🧠 Understand It • 📈 Scale It

</h3>

