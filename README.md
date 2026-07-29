<h1 align="center">Hi 👋, I'm Rudra Patel</h1>
<h3 align="center">Backend & Distributed Systems Engineer | Building things that scale, break, and get fixed</h3>

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=22&duration=3000&pause=1000&color=6AD3F0&center=true&vCenter=true&width=600&lines=SDE+Intern+%40+Spreadd+Adtech;Building+distributed+key-value+caches;Architecting+microservices+that+don't+fall+over;Competitive+Programmer+%7C+Codeforces+Specialist" alt="Typing SVG" />
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=Rudy-123&label=Profile%20Views&color=0e75b6&style=flat" alt="Profile views" />
  <img src="https://img.shields.io/github/followers/Rudy-123?label=Followers&style=social" alt="GitHub followers" />
</p>

---

## About Me

```js
const rudraPatel = {
    location: "Gandhinagar, Gujarat, India",
    education: "B.Tech Computer Engineering @ Pandit Deendayal Energy University (2023-2027)",
    currentRole: "SDE Intern @ Spreadd Adtech Pvt. Ltd (May - Jul 2026)",
    currentFocus: ["Distributed Systems", "Backend Engineering", "System Design", "Quant Finance"],
    achievements: [
        "Codeforces Specialist — 500+ problems solved, peak rating 1422 🧩",
        "LeetCode — 400+ problems solved, peak rating 1805 💯",
        "Qualified Stage 2, International Quant Championship 2026 (top 20% globally) 📈",
        "Cybersecurity Head @ ENCODE — mentored 50+ students, ran CTFs 🔐"
    ],
    funFact: "I've automated everything in my life except waking up on time"
};
```

## 💼 Professional Experience

**🖥️ SDE Intern** — *Spreadd Adtech Pvt. Ltd* · May 2026 – Jul 2026
- Built a distributed in-memory KV cache with quorum-based replication and automatic replica failover
- Built a sharded coordinator service enabling online shard expansion with zero-downtime key migration

## 🚀 Featured Projects

### ⚡ [Distributed KV Cache](https://github.com/Rudy-123)
A C++20 in-memory key-value store with distributed replication and dynamic sharding.
- O(1) GET/SET/DEL with LRFU-inspired eviction and O(log N) TTL scheduling
- Quorum-acknowledged primary–replica replication with heartbeat failure detection and auto-promotion
- Node.js/Express coordinator (MongoDB-backed) for online shard expansion via dual hash-ring routing

**Tech Stack:** `C++20` `Node.js` `MongoDB` `Multithreading`

### 🚄 [BookMyTrain](https://github.com/Rudy-123)
An 8-service railway reservation platform — 7 domain microservices + API Gateway, Saga orchestration, Kafka-driven events.
- 3-layer concurrency control: Redis Lua locks, PostgreSQL `FOR UPDATE NOWAIT`, version-based CAS
- Cut train-search latency >75% (200ms → <50ms) via Elasticsearch + Kafka sync
- Resilient gateway: 3-state Circuit Breaker + Redis ZSET sliding-window rate limiting
- Event-driven payments: Razorpay webhooks, Kafka `payment.success`/`booking.confirmed`, SendGrid notifications

**Tech Stack:** `Node.js` `Kafka` `Redis` `PostgreSQL` `Elasticsearch` `Docker`

### 📊 [Backtesting Engine](https://github.com/Rudy-123)
Config-driven Python backtesting engine with data-feed, execution, portfolio, and analytics modules.
- Parallelized 64 strategy configs across 8 workers — 88% faster grid search, 83% smaller storage (Snappy + Parquet)
- Dockerized + AWS EventBridge–Lambda–S3 pipeline ingesting Binance OHLCV every 15 min
- Improved historical PnL from -$39.1K → +$17.9K, cut max drawdown 73% using EMA/ATR/RSI regime filters

**Tech Stack:** `Python` `AWS` `Docker` `Pandas`

## 🛠️ Tech Arsenal

**Languages**

![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

**Backend & Data**

![Node.js](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white)
![Express](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka-000000?style=for-the-badge&logo=apachekafka&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![Elasticsearch](https://img.shields.io/badge/Elasticsearch-005571?style=for-the-badge&logo=elasticsearch&logoColor=white)

**Systems & Cloud**

![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)

## 🏆 Competitive Programming

<p align="left">
  <img src="https://img.shields.io/badge/Codeforces-Specialist%20(1422)-1E88E5?style=for-the-badge&logo=codeforces&logoColor=white" alt="Codeforces"/>
  <img src="https://img.shields.io/badge/LeetCode-1805%20Rating-FFA116?style=for-the-badge&logo=leetcode&logoColor=white" alt="LeetCode"/>
</p>

- 🥇 **Codeforces:** 500+ problems solved · Peak rating **1422 (Specialist)**
- 🥇 **LeetCode:** 400+ problems solved · Peak rating **1805**
- 📈 **International Quant Championship (IQC) 2026:** Qualified for Stage 2 — top 20% globally

> 🔗 Live, auto-updating CP stats can be embedded here using [github-readme-stats](https://github.com/anuraghazra/github-readme-stats) or [cp-badges](https://github.com/kannishk/cp-badges) — see note at the bottom.

## 📊 GitHub Analytics

![Rudra's GitHub stats](https://github-stats-extended.vercel.app/api?username=Rudy-123&show_icons=true&theme=tokyonight&include_all_commits=true)

![Top Languages](https://github-stats-extended.vercel.app/api/top-langs/?username=Rudy-123&layout=compact&langs_count=8&theme=tokyonight)

![GitHub Streak](https://github-readme-streak-stats.herokuapp.com/?user=Rudy-123&theme=tokyonight)

## 🎯 Leadership & Community

- **Cybersecurity Head, ENCODE** — Mentored 50+ students through hands-on security workshops, organized Capture The Flag (CTF) competitions

## 🌟 Let's Connect

<p align="left">
<a href="https://linkedin.com/rudra" target="_blank"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
<a href="mailto:rudrapatel47108@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>
<a href="https://github.com/Rudy-123" target="_blank"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/></a>
</p>

[![Snake Animation](https://raw.githubusercontent.com/platane/platane/output/github-contribution-grid-snake-dark.svg)](https://github.com/Rudy-123)

<p align="center"><i>"O(1) lookups, O(log N) patience, O(n) coffee."</i></p>
