# Ahmad Raza

Full-stack dev, mostly JS/TS across web and mobile, with some AI work mixed in. Background in Computer Science, currently finishing an MSc at Ulster University where I'm researching continuous authentication for my dissertation.

I like knowing how the tools I use actually work, not just that they work. If something feels like magic, I usually end up rebuilding a small version of it myself just to see what's actually happening underneath.

**Building right now:** [Pulzie](https://github.com/ahmadraza100/pulzie), a small reactive framework I wrote from scratch, ~300 lines, no dependencies
**Researching right now:** continuous biometric authentication, for my dissertation

---

## What I use

**Full-stack:** JavaScript, TypeScript, React, Next.js, React Native, Node.js, Express, TanStack Query, Zustand, Tailwind, REST, GraphQL, Prisma, Postgres, MongoDB, Vite, Zod

**AI:** Python, Flask, LangChain, OpenAI API

**Infra:** Docker, AWS, Firebase, Git

---

## Projects

**[Pulzie](https://github.com/ahmadraza100/pulzie)**
A reactive UI framework built from scratch in plain JavaScript — no libraries, no compiler plugins. Signals drive the reactivity, so only the effects that actually read a changed signal re-run, and the DOM gets patched directly instead of doing a full re-render. About 300 lines total: signals, batching, a small virtual DOM diff/patch, JSX, undo/redo. Built it mainly to understand what frameworks like Solid and Vue are actually doing under the hood.

**[ContinuousAuth](https://github.com/ahmadraza100/continuousauth-edge)**
Biometric authentication that doesn't stop checking once you're logged in. Runs on a Raspberry Pi 4, no cloud involved. It keeps checking your face and voice throughout a session, and if someone else takes over, the trust score drops and it forces re-auth in about 20 seconds. This was my MSc dissertation project, cyber security focus. The fusion model held up well under 7-fold cross-validation (AUC 0.978, EER 6.7%), and every access decision gets written to a smart contract so the audit log can't quietly be edited later.

---

Open to full-stack or AI roles, ideally somewhere I can work close to the actual system rather than just the surface of it.
