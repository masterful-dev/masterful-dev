<h1 align="left">Masterful</h1>

**I build the applications I keep missing.**

I'm a software developer from Poland. When a tool I need doesn't exist, or exists but gets in my way,
I write my own: desktop applications first, and the engines underneath them when that is what it takes.

```text
1. I need a tool.
2. It doesn't exist, or it fights me.
3. I build it.
4. I use it every day, so it gets finished.
```

## Applications

**Mission Control** — a native desktop control room for everything that runs on my workstation.
Every service is registered there and started or stopped from one window of switches and status lights,
so I always know what is running, on which hardware, and at what cost.

**Dictation** — hold a key, speak, and the words appear as you talk. It runs offline, on the CPU alone.

**DSH++** — a workspace for long-running AI missions: a mission queue with priorities, a mission wizard,
an away-from-keyboard mode, a resource manager and mission memory.

## Tools and engines

**WARP** — an AI inference engine I wrote from scratch in C++/CUDA, in the same spirit as llama.cpp or vLLM,
built for one target: the Tesla V100, on one card or on two cards working as one.

- Reads standard GGUF model files exactly as they are. Not one bit of the weights is changed.
- One codebase for every model. No forks and no per-model copies.
- Ships with an OpenAI-compatible server.
- Every change is measured on every model. If any of them gets slower, the change does not go in.

Measured on two cards from 2017 with a 100,000-token context: about 200 tokens per second of writing
and about 5,570 tokens per second of prompt reading on a 125B model (state of 19 November 2026).

WARP videos are on my YouTube channel: **[Masterful Dev](https://www.youtube.com/@masterful-dev)**.

## How I work

- **Build what is missing.** Every project here started as something I needed myself.
- **Local first.** Everything runs on my own hardware before I pay anybody.
- **A number before and a number after.** Nothing is "faster" until it is measured.
- **Quality is not for sale.** No lossy shortcut goes in without a written reason.
- **Private until finished.** Repositories open when the work is ready to be seen.

## Stack

`C++` `CUDA` `Python` `Rust` `Linux` `GGUF` `OpenAI-compatible APIs`

## Find me

▶ **YouTube:** [Masterful Dev](https://www.youtube.com/@masterful-dev)

---

<sub>Small print: the drives in my machine are named after towns from an old MMORPG. The biggest one is, of course, Aden.</sub>
