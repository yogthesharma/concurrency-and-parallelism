# Concurrency and Parallelism

Standalone learning repo. Work here on its own — no other repos required.

**Phase (for your own roadmap):** Foundations

## Context

Modern apps juggle many tasks at once. Threads, async/await, event loops, and actors are different tools for that job — with different failure modes. Study them here without pulling in networking or backend repos.

This repository is the single place for everything related to **Concurrency and Parallelism**: notes, exercises, and small projects. Clone it, open it, and treat it as a complete unit of study.

## Scope

- Concurrency vs parallelism (clear definitions)
- Threads, mutexes, and shared-memory pitfalls
- Async / await and the event loop
- Race conditions, deadlocks, livelocks
- Actor model and message-passing intuition
- When to choose threads vs async vs processes

## Outcomes

When you are done with this repo, you should be able to:

- Diagnose a race or deadlock from a description / small example
- Choose a concurrency model that fits the workload
- Write small demos that show correct vs broken concurrent code

## How to work in this repo

1. Read / write concept notes under `notes/`.
2. Solve practice problems under `exercises/`.
3. Ship at least one small project under `projects/` that forces the ideas to stick.
4. Tick the checklist below as you go.

You do not need any other curriculum repo open while you work here.

## Layout

```
concurrency-and-parallelism/
├── README.md       # Context and checklist (this file)
├── notes/          # Concept write-ups
├── exercises/      # Practice problems and solutions
└── projects/       # Mini builds that apply the topic
```

## Progress

- [ ] Core concepts noted
- [ ] Exercises completed
- [ ] Mini-project shipped
- [ ] Can explain the main ideas without looking anything up

## Resources

Add books, docs, courses, and articles here as you find them. Keep this list local to this topic.

---

_This repo is independent. Progress elsewhere does not block work here._
