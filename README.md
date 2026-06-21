# Hi, I'm Kartavya 👋

CS undergrad at BITS Pilani, Goa Campus — graduating May 2026. I like building backend systems and low-level infrastructure — and shipping tools that actually get used.

Currently interning as an SDE at **Commvault**, where I work on security signal ingestion pipelines — async vendor API pulls, threat detection, and resilient distributed processing. Previously built real-time GPU-accelerated 3D pose estimation pipelines at **Quidich Innovation Labs** for broadcast and AR/VR.

## What I've built

**[MiniRedis](https://github.com/Kartey426/MiniRedis)** — A Redis clone in C++. Custom hashtable with incremental rehashing, AVL-backed sorted sets, TTL expiry via a min-heap, non-blocking event loop with `poll()`, and a thread pool for async work. Built to understand how Redis actually works, not as a tutorial.

**[Screendrop](https://github.com/Kartey426/Screendrop)** — Push screenshots from your laptop to your tablet instantly over local WiFi. Go WebSocket server and clipboard watcher. No cloud, no app install, sub-second latency. Built because I needed it.

**[3D Pose Estimation](https://github.com/harshitkapoor03/3D_Pose_estimation)** — Multi-camera 3D pose pipeline for sports analytics, built during my internship at Quidich. YOLO-based detection, FastReID for player re-identification, and triangulation across camera views. (contributed via a separate account)

**[Distributed Rate Limiter & Mini API Gateway](https://github.com/Kartey426/ratelimiter)** — Token bucket and sliding window rate limiting backed by Redis, with every check-and-increment done atomically via a Lua script so it stays correct across multiple gateway instances, not just one process. Includes a concurrent Go load-test client built to prove the limit holds under real concurrency.

## Tech I work with

`C++` `Python` `C#` `Go` `PyTorch` `Redis`  `async systems` `WebSockets` `distributed systems`

## Connect

- 💼 [LinkedIn](https://www.linkedin.com/in/kartavyadubey)
- 📬 <kartavyadubey05@gmail.com>
