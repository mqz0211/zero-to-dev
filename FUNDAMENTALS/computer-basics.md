# Computer Basics

> Start here if terms like "RAM," "CPU," or "SSD" feel like a foreign
> language. Every other file in this repo assumes you've read this one.

## The four things every computer has

Think of a computer like a kitchen. Understanding these four parts
explains almost every "why is my computer slow" or "why does this
matter for programming" question you'll ever have.

### CPU (Central Processing Unit) — the chef

The CPU is the part that actually *does* things — runs your code,
calculates, makes decisions. It's rated in **GHz** (gigahertz), which
roughly means "how many instructions per second it can execute," and
**cores**, which means "how many things it can do at the same time."

**Why it matters for you:** when your code "runs slow," it's often
because it's asking the CPU to do more work than it needs to — this is
what "algorithm efficiency" (Big O notation) is actually about.

### RAM (Random Access Memory) — the countertop

RAM is short-term, fast memory the CPU uses to hold whatever it's
actively working on. It's measured in **GB** (gigabytes). Unlike a
countertop, RAM is *wiped clean* when you turn the computer off —
that's why unsaved work disappears if your computer crashes.

**Why it matters for you:** "running out of memory" errors mean your
program tried to hold more data in RAM than was available. This is a
real, common bug in data science and game development.

### Storage (SSD/HDD) — the pantry

Storage is where things live permanently — your files, your operating
system, your installed programs — even when the power is off. Modern
computers use **SSDs** (fast, no moving parts) instead of older
**HDDs** (slower, spinning disks).

**Why it matters for you:** this is where your code, your Git
repositories, and your saved files actually live between sessions.

### GPU (Graphics Processing Unit) — the specialist chef

A GPU is built to do *many simple calculations at once*, originally for
rendering graphics. It turns out this is also exactly what machine
learning and AI training need — which is why "do I have a GPU" is such
a common question in the AI/ML world.

**Why it matters for you:** if you go down the [AI Engineer](../ROADMAPS/ai-engineer.md)
or [Game Developer](../ROADMAPS/game-developer.md) path, GPUs become
central to your work.

## The operating system (OS)

The OS (Windows, macOS, Linux) is the software that manages all four
parts above and lets your programs talk to them without you having to
control the hardware directly. Almost all professional software
development happens on **macOS or Linux** — see
[`linux.md`](linux.md) for why Linux specifically matters so much in tech.

## Files, folders, and paths

A **file path** is just an address for where something lives on your
storage — e.g. `/Users/you/Documents/project/main.py` (macOS/Linux) or
`C:\Users\you\Documents\project\main.py` (Windows). You'll type these
constantly once you start using the command line — see
[`linux.md`](linux.md) for the command-line basics.

## Binary — the one idea underneath everything

Computers only understand two states: on and off, represented as `1`
and `0`. Everything — text, images, this very file — is ultimately
stored as sequences of `1`s and `0`s (bits). You don't need to think
about this daily, but it explains *why* things like "8-bit," "32-bit,"
and "64-bit" systems are named the way they are.

## ✅ Check yourself

You're ready to move on when you can explain, in your own words:
- The difference between RAM and storage
- Why more CPU cores can make a program run faster
- What a file path is

## Next steps

- [`linux.md`](linux.md) — the command line and why developers live in it
- [`networking.md`](networking.md) — what actually happens when you visit a website
- Pick your [career path](../README.md#-choose-your-path) to see how this fits into the bigger picture
