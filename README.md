<h1 align="center">Hi, I'm Sudhanva 👋</h1>

<p align="center">
  <b>Backend & Distributed Systems Engineer &nbsp;|&nbsp; Ex BlackRock &nbsp;|&nbsp; MS CS @ Northeastern &nbsp;|&nbsp; Open to SWE / Backend / Infra roles</b>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/sudhanva-devanathan">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="mailto:sudhanva20@gmail.com">
    <img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
  <img src="https://img.shields.io/badge/Open%20to%20Work-2ea44f?style=for-the-badge" />
  <a href="https://github.com/sdevanathan96/sdevanathan96/blob/main/Sudhanva_Resume.pdf">
    <img src="https://img.shields.io/badge/Resume-PDF-red?style=for-the-badge&logo=adobeacrobatreader&logoColor=white" />
  </a>
</p>

---

### 🧭 About Me

- 🎓 MS Computer Science @ Northeastern University (GPA: 3.84), May 2026, focused on distributed systems and advanced algorithms
- 🏦 6 years at BlackRock (SWE I to SWE II), building data pipeline infrastructure on the Aladdin platform for 130+ clients and 100K+ portfolios
- 🧠 At BlackRock: a Python pipeline processing 100M+ rows nightly, a Java Spring Boot config service over gRPC and Kafka that cut daily DB connections by 80%, and a Python asyncio monitoring system that improved on time failure detection by 40%
- 🔧 Outside work, I build systems from scratch when I want to actually understand them. The latest is a Redis compatible server in async Rust.
- 🔍 Open to SWE / Backend / Infrastructure roles

---

### 🚀 Featured Projects

| Project | Stack | Highlights |
|--------|-------|------------|
| [**rusty-redis**](https://github.com/sdevanathan96/rusty-redis) | Rust · Tokio | Redis compatible server that grew out of the CodeCrafters Redis track: single owner keyspace task with no global lock, zero copy two pass RESP parser, strings, lists, and streams with blocking commands (BLPOP, BLMOVE, XREAD BLOCK). Differentially tested byte for byte against real Redis in CI; fuzzing found a preallocation DoS and two remote crashes, all fixed. Unpipelined, it runs at 0.70x to 0.88x of Redis's throughput with lower p99 latency on 9 of 10 commands |
| [**Distributed Key-Value Store**](https://github.com/sdevanathan96/Distributed-Key-Value-Store) | Go · gRPC · Protobuf | Raft consensus from scratch (no third party library), consistent hashing with virtual nodes for sharding, WAL + LSM tree storage with Bloom filters and multilevel compaction, crash recovery via WAL replay, concurrency verified under Go's race detector |
| [**HA Layer 7 Load Balancer**](https://github.com/sdevanathan96/hA-L7-lb-with-retry) | Go · Redis · Docker | Redis Pub/Sub state synchronization across LB instances, 5 routing policies (Round Robin, Random, Least Connections, Weighted, IP Hash), retries restricted to idempotent requests so a retry can never double write, 6,000 to 7,500 RPS sustained at under 10ms average latency |
| [**Probabilistic Chord DHT**](https://github.com/sdevanathan96/probabilistic-chord) | C++11 · Unix Sockets | Three pluggable routing strategies (finger table baseline, Cuckoo filter, Quotient filter); held O(log n) lookup hops while cutting maintenance traffic about 50%, benchmarked from 8 to 1024 nodes running as separate OS processes |
| [**code-flash**](https://github.com/sdevanathan96/code-flash) | Java · Spring Boot · PostgreSQL | LeetCode spaced repetition tracker using SM-2; Strategy pattern for pluggable SRS engines, Observer pattern for solve events, Flyway migrations |

Also: [Deep RL for Atari](https://github.com/sdevanathan96/DQN) (DQN + PPO in PyTorch, coursework)

---

### 🛠️ Tech Stack

**Languages**

![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=c%2B%2B&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)

**Frameworks & Infra**

![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![gRPC](https://img.shields.io/badge/gRPC-4285F4?style=flat-square&logo=google&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)
![Tokio](https://img.shields.io/badge/Tokio-000000?style=flat-square&logo=rust&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-FF9900?style=flat-square&logo=amazonaws&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)

**Databases**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Cassandra](https://img.shields.io/badge/Cassandra-1287B1?style=flat-square&logo=apachecassandra&logoColor=white)

---

### 📚 What I'm Currently Working On

- 🦀 **[rusty-redis](https://github.com/sdevanathan96/rusty-redis)**: packing small values into compact storage to close the memory gap with Redis (stream entries are 196 B vs Redis's 18 B today)
- 🤖 **[asyncio-fleet-telemetry](https://github.com/sdevanathan96/asyncio-fleet-telemetry)**: Python 3.14 telemetry pipeline simulating a warehouse robot fleet
- ☸️ **Certified Kubernetes Administrator (CKA)**: in progress, target [Dec 2026]
- ☁️ **AWS Solutions Architect Associate**: in progress, target [Nov 2026]
