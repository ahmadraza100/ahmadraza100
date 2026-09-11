# Ahmad Raza

Full-stack developer building production-grade web and mobile applications, with a background in Computer Science and working knowledge of AI-integrated systems. Currently completing an MSc in Computer Science at Ulster University, researching continuous authentication systems.

I care about understanding systems at the mechanism level, not just shipping features that work by coincidence. That shows up in how I build: proper architecture over quick hacks, and code I can actually explain the tradeoffs behind, including the framework internals most developers only ever consume.

**Currently building:** [Pulzie](https://github.com/ahmadraza100/pulzie), a reactive UI framework built from scratch, ~300 lines, no dependencies
**Currently researching:** Continuous biometric authentication for my MSc dissertation

---

## What I Work With

**Full-Stack Development**
JavaScript · TypeScript · React · Next.js · React Native · Node.js · Express · TanStack Query · Zustand · Tailwind CSS · REST APIs · GraphQL · Prisma · PostgreSQL · MongoDB · Vite · Zod

**AI & Machine Learning**
Python · Flask · LangChain · OpenAI API

**Infrastructure**
Docker · AWS · Firebase · Git

---

## Selected Work

**[Pulzie](https://github.com/ahmadraza100/pulzie)**
A reactive UI framework built from scratch in vanilla JavaScript, no libraries or compiler plugins. Signals drive reactivity: only the effects that read a changed signal re-run, and the DOM patches surgically instead of re-rendering. About 300 lines covering reactive signals, batched updates, virtual DOM diffing, JSX, and undo/redo, built to understand what's actually happening inside frameworks like Solid and Vue, not just to use them.

**[ContinuousAuth](https://github.com/ahmadraza100/continuousauth-edge)**
Continuous biometric authentication running entirely on a Raspberry Pi 4, no cloud. Most systems verify identity once at the door and stop; this one keeps checking face and voice throughout the session, decaying a trust score and forcing re-authentication within about 20 seconds if the wrong person takes over. Built for my MSc Cyber Security dissertation at Ulster University. Fusion model evaluated under 7-fold cross-validation (AUC 0.978, EER 6.7%), with every access decision logged to a smart contract for tamper-evident audit.

---

*Open to full-stack or AI engineering roles where I can work close to the system, not just the surface.*
