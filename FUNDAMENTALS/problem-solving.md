# What Does a Developer Actually Do All Day?

> Not what movies show you. Here's an honest picture, plus the actual
> thinking process behind writing code.

## The honest answer

A developer spends most of their time:
- **Reading** existing code (far more than writing new code)
- **Breaking problems into smaller problems**
- **Searching** for how to do specific things (yes, constantly — this
  is normal, not a sign you're bad at this)
- **Testing** whether what they built actually works
- **Fixing** things that don't work the way they expected (debugging)
- **Talking** to other people about what to build and why

Writing brand-new code from a blank file is a smaller part of the job
than most beginners expect.

## The core skill: breaking problems down

This is the single most important skill in all of tech, and it's
learnable. Take a vague goal and keep asking "what smaller thing does
this actually require?" until each piece is small enough to solve on
its own.

**Example — "Build a to-do list app":**
1. Show a list of tasks on screen
2. Let the user type a new task and add it to the list
3. Let the user mark a task as done
4. Let the user delete a task
5. Save the list somewhere so it's still there after closing the app

Each of those is now small enough to actually start on. This is
exactly what [project sequencing](../PROJECTS/beginner-projects.md) in
this repo is built around.

## Debugging: the actual daily skill

When code doesn't work, resist the urge to guess randomly. Instead:

1. **Reproduce it** — make the bug happen again, reliably
2. **Read the error message** — actually read it, slowly; it usually
   tells you the file, the line, and what went wrong
3. **Isolate it** — comment out or remove code until the bug
   disappears, then you know exactly what caused it
4. **Check your assumptions** — print out variable values; often the
   bug is that a variable isn't what you assumed it was
5. **Search the exact error message** — you are almost never the first
   person to hit this exact error

## "I don't know how to do this" is a normal daily thought

Professional developers look things up constantly — official docs,
Stack Overflow, AI assistants, source code of libraries they use. The
skill isn't "knowing everything." The skill is **knowing how to find
and evaluate an answer quickly**, and understanding it well enough to
use it correctly.

## Reading code is a skill you have to practice on purpose

New developers often only ever write their own code and never read
anyone else's. Force yourself to read real projects on GitHub — you
don't need to understand every line; you're training your brain to
recognize patterns.

## Check yourself

Try this right now: pick any everyday task (making instant noodles,
getting ready for school) and break it into a numbered list of steps
small enough that someone with zero context could follow it exactly.
That's the same muscle you'll use to break down code problems.

## Next steps

You've now covered all four fundamentals. Time to pick a direction:

- [Choose your path](../README.md#-choose-your-path)
- [Beginner projects](../PROJECTS/beginner-projects.md) — start building
