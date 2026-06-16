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

### Featured work — distilled patterns from production systems

These are small, focused, **fully-tested** Go libraries that implement the
distributed-systems patterns I use day to day. Clean-room and original; each runs
with `go run ./example` and passes `go test -race`.

| Repo | What it shows |
|------|---------------|
| **[go-saga-orchestrator](https://github.com/mrchcoin/go-saga-orchestrator)** | Saga engine: ordered steps with **automatic compensation/rollback** on failure. Generic, transport-agnostic, race-tested. |
| **[idempotent-ledger](https://github.com/mrchcoin/idempotent-ledger)** | **Append-only, double-entry** money ledger with **idempotency keys** — retried requests apply exactly once; `Audit()` proves conservation. |
| **[ws-fanout-gateway](https://github.com/mrchcoin/ws-fanout-gateway)** | Topic-based **WebSocket fan-out hub**: lock-free single-goroutine core, slow-consumer backpressure, per-connection rate limiting. |

<!--
Optional: add a GitHub stats card once you have public activity, e.g.
![stats](https://github-readme-stats.vercel.app/api?username=mrchcoin&show_icons=true)
Leave it out until the repos are pushed, so it doesn't render empty.
-->
