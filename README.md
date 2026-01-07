# What Is It?
A ready‑to‑deploy AI‑powered gaming simulation accelerator that demonstrates how to build a modern, globally scalable gaming platform using Azure Cosmos DB NoSQL API with real‑time data modeling, partitioning, leaderboards, Change Feed, vector search, and RAG‑based intelligent player experiences.

# Overview
Modern gaming platforms demand:
- **Global availability**
- **Real-time responsiveness**
- **Massive scalability**
- **AI-driven personalization**

Azure Cosmos DB delivers these capabilities with:
- Multi-region writes
- Autoscale throughput
- Change Feed for event streaming
- Vector search for AI
- Field-level encryption
- RBAC and private endpoints

# What’s Included?
- Sample Gaming App schema and data with following collections
  - players
  - sessions
  - leaderboards
  - events
  - matches
- Database and collection provisioning with auto-scale throughput
- Leaderboard bucketing and RU tracking
- Data Seeding: Generate synthetic players across regions
- Simulation: Concurrent gameplay across regions
- Query: Retrieve top-K leaderboard results
- Change Feed: Pull recent events for live ops

Retrieval-Augmented Generation (RAG) with Azure Cosmos DB NoSQL API for Gaming Collections

This section demonstrates how to:
- Connect to Azure Cosmos DB NoSQL API
- Read sample documents from existing collections (`players`, `sessions`, `leaderboards`, `events`, `matches`)
- Generate embeddings using Azure OpenAI
- Store documents with embeddings in a new container with vector indexing
- Perform vector search queries for RAG scenarios

# Why Use This Accelerator?
- Try before you build: Explore Cosmos DB NoSQL API capabilities in a sandboxed Azure environment
- Accelerate time-to-value: Use pre-built components to jumpstart your implementation
- Showcase to stakeholders: Demonstrate real-world use cases like instant scalability, ultra low latency, global replication, and intelligent assistants
