# think-first ▸

> Before you prompt, **think first.**

A open-source challenge platform for software engineers who use AI tools daily  
and refuse to let that turn them into copy-paste machines.

---

## The problem

AI coding assistants are incredible. They also make it dangerously easy to stop thinking.

You ask, it answers. You paste, it works. You ship — and somewhere along the way,  
you stopped understanding what you shipped.

This repo exists for engineers who noticed that drift and want to fight it.

---

## What is this?

**think-first** is a collection of progressive programming challenges focused on  
concepts that separate Senior engineers from Staff and Principal engineers.

Not leetcode puzzles. Not syntax quizzes.

Real architectural decisions. Concurrency trade-offs. Framework internals. System design.  
The kind of problem where AI gives you an answer instantly — but you need to **understand why**  
before that answer is worth anything in production.

Each challenge follows a structure:

| Section | Purpose |
|---|---|
| 📖 **Concept** | The mental model behind the problem |
| 💡 **Hints** | Nudges to guide your reasoning — without giving it away |
| `</>` **Solution** | Annotated code with full explanation |
| 🎯 **Takeaway** | The one thing a Staff engineer carries from this |

---

## Who this is for

- Senior engineers transitioning toward Staff / Principal roles
- Developers who use AI heavily and want to stay sharp
- Anyone who's caught themselves not knowing _why_ their AI-generated code works
- Teams that want to build a culture of engineering depth, not just velocity

---

## Tech stack covered

| Area | Topics |
|---|---|
| **Spring Boot** | Bean lifecycle, circular dependencies, virtual threads, tracing |
| **Quarkus** | GraalVM native image, reflection, build-time vs runtime |
| **Concurrency** | Platform threads vs virtual threads, structured concurrency |
| **Architecture** | Hexagonal, Clean, CQRS, Strangler Fig migration |
| **Distributed Systems** | Idempotency, distributed tracing, Saga pattern |
| **Observability** | OpenTelemetry, Micrometer, structured logging, trace correlation |
| **Messaging** | Kafka consumer groups, exactly-once semantics, dead letter queues |
| **Data** | Transaction isolation, connection pool tuning, N+1 detection |

> Primarily Java-focused, but the architectural concepts apply across ecosystems.

---

## Running locally

The platform is a single React component. No backend, no database.

```bash
# Clone
git clone https://github.com/your-username/think-first
cd think-first

# Install
npm install

# Run
npm run dev
```

Open `http://localhost:3000` and pick a challenge.

---

## Contributing

New challenges are welcome. The bar is high on purpose.

A good challenge must:

- Target a concept that matters at Senior level and above
- Not be googleable in 10 seconds
- Have a **Takeaway** that a Staff engineer would genuinely say out loud in a review
- Include code that is real, not toy examples

### Challenge format

```markdown
---
id: 7
level: Staff           # Senior | Staff | Principal
tag: Kafka
title: Consumer Group Rebalancing under load
description: |
  Your Kafka consumer group is rebalancing every 2 minutes under high load,
  causing processing gaps. How do you diagnose and fix this without reducing throughput?
concept: |
  ...
hints:
  - ...
solution: |
  // ...
takeaway: |
  ...
---
```

Open a PR with your challenge in `challenges/` and a brief justification  
for why it belongs at the level you selected.

---

## Philosophy

This project is not anti-AI.

AI is a force multiplier — for engineers who still know how to think.  
The goal is not to avoid AI tools. It's to stay in the driver's seat when you use them.

The best engineers in the next decade will be the ones who use AI  
**with full understanding**, not in place of it.

**think-first** is a place to maintain that edge.

---

## License

MIT — use it, fork it, bring it to your team.

---

<p align="center">
  Made by engineers who refused to stop thinking. <br/>
  Star it if you believe the craft still matters. ⭐
</p>
