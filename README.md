# Learning Resources (Curated, Not a Link Dump)

A living, opinionated collection of learning resources for **programming + systems + game/engine dev** — curated to help you go from *“I kinda get it”* to *“I can build it and debug it.”*

This repo is for people who want a **path**, not 500 random links.

---

## How to use this repo

If you’re new here, do this:

1. **Pick a track** (below).
2. **Follow the order** — the order is the whole point.
3. When you get stuck, jump to **Tools & Debugging** and come back stronger.

If you already know what you want:
- Use the topic pages in `docs/` and grab what you need.

---

## Tracks (pick one)

### 1) Core Programming Track (Start Here)
Best if you’re building fundamentals.
- C/C++ basics → build tools → debugging mindset → clean code habits

➡️ Start: `docs/00-roadmap.md` (then `docs/cpp.md`)

### 2) Graphics Track (Rendering Brain Upgrade)
Best if you want to understand rendering beyond “it works”.
- math → OpenGL/Vulkan concepts → render architecture → performance

➡️ Start: `docs/math.md` then `docs/graphics.md`

### 3) Game/Engine Track (Build Real Systems)
Best if you want to make engines/tools and not get lost.
- ECS → assets → scenes → scripting → physics → editor/tooling

➡️ Start: `docs/engine-architecture.md`

---

## Repo structure

- `README.md` — overview + tracks (you are here)
- `docs/00-roadmap.md` — recommended order + milestones
- `docs/cpp.md` — language fundamentals + modern C++ habits
- `docs/math.md` — the math you actually use
- `docs/graphics.md` — rendering / APIs / pipelines
- `docs/engine-architecture.md` — ECS, assets, scenes, tools
- `docs/tools-debugging.md` — debuggers, sanitizers, profilers, tracing
- `docs/projects.md` — small projects to turn knowledge into skill

> Tip: Don’t read everything. **Build something small every week**.

---

## What this repo is (and isn’t)

✅ **This is:**
- A curated list with *reasons* and *order*
- Focused on understanding + building + debugging
- Beginner-friendly, but not “hand-holdy”

❌ **This is not:**
- A mega-list of every tutorial ever
- A substitute for practice
- A place for “cool link, no context”

---

## Resource legend

Each resource is tagged like this:

- **[B]** Beginner — no assumptions
- **[I]** Intermediate — you can code comfortably
- **[A]** Advanced — you want deeper internals

Types:
- **(Book)**, **(Course)**, **(Video)**, **(Docs)**, **(Article)**, **(Tool)**

---

## Quality rules (why this repo stays useful)

Every link must answer:
- **Why is it here?**
- **When should someone use it?**
- **What should they know first?**

If a resource is outdated, paywalled without alternatives, or low-signal → it gets removed.

---

## Contributing

Contributions are welcome — **if they keep the signal high**.

### Add a resource
1. Put it in the correct `docs/*.md` file.
2. Use this exact format:

```md
- **Title** — (Type) — [B/I/A]  
  *Why:* what you’ll learn / why it matters  
  *Prereq:* what you should know first (or “none”)  
  *Time:* ~how long it takes (optional)
