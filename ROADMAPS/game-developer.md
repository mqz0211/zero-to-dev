# 🎮 Game Developer Roadmap

**For people who want to:** build games — from core logic to engine to
shipped release.
**Estimated time (part-time):** 8–12 months to internship/first-release-ready.

## Stage 0 — Fundamentals (2–3 weeks)
- [ ] [Computer basics](../FUNDAMENTALS/computer-basics.md)
- [ ] [Linux / command line basics](../FUNDAMENTALS/linux.md)
- [ ] [Problem-solving mindset](../FUNDAMENTALS/problem-solving.md)

## Stage 1 — Programming fundamentals (6–8 weeks)
- [ ] Pick C# (Unity) or C++ (Unreal/custom engines) — see the decision
      note below
- [ ] Variables, control flow, functions
- [ ] Object-oriented programming (classes, inheritance) — games use
      this constantly (a `Player`, an `Enemy`, an `Item` are all objects)
- [ ] Basic data structures: arrays, lists

**Decision: which language/engine?**
| If you want... | Pick |
|---|---|
| Fastest path to a finished, shippable game | Unity (C#) or Godot (GDScript/C#) |
| AAA-style graphics, willing to go deeper into low-level code | Unreal Engine (C++) |
| Full control, building your own engine eventually | C++ from scratch with a library like SDL |

## Stage 2 — Game math & physics (4 weeks)
- [ ] Vectors (position, direction, velocity)
- [ ] Basic trigonometry (angles, rotation)
- [ ] Collision detection fundamentals
- [ ] Frame-rate independence (delta time — a classic beginner bug source)

## Stage 3 — Pick an engine and go deep (6–8 weeks)
- [ ] Scene/level structure
- [ ] Game objects, components, prefabs
- [ ] Input handling
- [ ] Basic UI (menus, HUDs)
- [ ] Animation basics (sprite or skeletal)

**Build as you go:** clone small, complete games first — see
[`PROJECTS/beginner-projects.md`](../PROJECTS/beginner-projects.md)
(Pong → Breakout → simple platformer).

## Stage 4 — Game systems (6 weeks)
- [ ] State machines (menu state, playing state, paused, game over)
- [ ] Simple AI (enemy behavior — patrol, chase, basic decision trees)
- [ ] Save/load systems
- [ ] Audio integration

## Stage 5 — Polish & game feel (4 weeks)
The difference between an amateur and professional-feeling game is
almost entirely here:
- [ ] Juice: screen shake, particle effects, hit-stop, sound feedback
- [ ] Playtesting and iterating on feedback
- [ ] Performance basics (why is my game dropping frames?)

## Stage 6 — Ship something (4–6 weeks)
- [ ] Finish a small, complete game — scope it down aggressively; a
      finished small game beats an unfinished ambitious one
- [ ] Publish it: itch.io is free and the standard first stop
- [ ] Write a devlog or postmortem — this is genuinely valued in game
      dev portfolios

## Stage 7 — Build a portfolio (ongoing)
- [ ] 2–3 finished, playable games (even small ones)
- [ ] A GitHub repo per game with a proper README and, ideally, a
      playable web/downloadable build
- [ ] A devlog or blog documenting your process and decisions
- [ ] See [`CAREERS/portfolio.md`](../CAREERS/portfolio.md)

## ✅ You're ready for an internship interview when you can:
- Explain how you'd implement basic enemy AI, from scratch, on a whiteboard
- Talk through a finished game in your portfolio: what was hard, what
  you'd redo
- Explain delta time and why frame-rate independence matters

## Resources for this path
- [Free courses →](../RESOURCES/free-courses.md)
- [Books →](../RESOURCES/books.md)
- [YouTube channels →](../RESOURCES/youtube.md)
- [Websites & tools →](../RESOURCES/websites.md)
