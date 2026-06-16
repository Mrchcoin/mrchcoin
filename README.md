<!--
This is your GitHub PROFILE README. It renders at the top of github.com/mrchcoin.
To publish it: create a repo named EXACTLY "mrchcoin" (same as your username),
add this file as README.md, and push. See GITHUB-SETUP.md for the commands.
-->

# Mohamad Reza Chegini

**Principal Backend & Platform Engineer** — distributed systems in Go & C/C++, Kubernetes-native infrastructure, event-driven fintech.

15+ years building the systems other engineers build on: a multi-tenant cloud (IaaS) platform, cryptocurrency exchange engines, BNPL platforms, and immutable ledgers. I care about systems that stay correct under failure — sagas, idempotency, clear domain boundaries, and observability you can reason about.

- 🛠 **Core:** Go · C/C++ · Java · Kubernetes · Kafka/Redpanda · PostgreSQL · gRPC · WebSocket
- 🧭 **Patterns:** DDD · CQRS · Event-Driven Architecture · Saga Orchestration · Idempotent Processing
- ☁️ **Platform:** KubeVirt · kube-ovn · k0smotron · Rook-Ceph · ORY (Kratos/Oathkeeper) · Vault
- 📫 **Reach me:** mrchcoin@gmail.com · [linkedin.com/in/mrchcoin](https://linkedin.com/in/mrchcoin)
- 🌍 Open to senior/principal **remote** backend & platform roles (and relocation: UAE · EU · Singapore)

### Featured — distilled patterns, across languages

Small, focused, **fully-tested** libraries implementing the distributed-systems
patterns I use in production. Clean-room and original; each builds, runs, and is
verified under a race/thread sanitizer where applicable.

**Go**
- **[go-saga-orchestrator](https://github.com/mrchcoin/go-saga-orchestrator)** — saga steps with automatic compensation/rollback; race-tested.
- **[idempotent-ledger](https://github.com/mrchcoin/idempotent-ledger)** — append-only, double-entry ledger with idempotency keys; `Audit()` proves conservation.
- **[ws-fanout-gateway](https://github.com/mrchcoin/ws-fanout-gateway)** — lock-free WebSocket fan-out hub with slow-consumer backpressure + rate limiting.

**Java · C# · C++**
- **[idempotent-ledger-java](https://github.com/mrchcoin/idempotent-ledger-java)** — the ledger in Java 21 (JUnit 5, thread-safe).
- **[saga-orchestrator-dotnet](https://github.com/mrchcoin/saga-orchestrator-dotnet)** — the saga in async C#/.NET 8 (`Task`-based, xUnit).
- **[cpp-threadpool](https://github.com/mrchcoin/cpp-threadpool)** — header-only C++17 thread pool with `std::future` results; ThreadSanitizer-clean.

<!--
Optional: add a GitHub stats card once you have public activity, e.g.
![stats](https://github-readme-stats.vercel.app/api?username=mrchcoin&show_icons=true)
Leave it out until the repos are pushed, so it doesn't render empty.
-->
