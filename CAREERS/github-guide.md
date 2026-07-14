# Making Your GitHub Profile Look Professional

Your GitHub is the single most-checked link on a student resume in
tech. Treat it like the front door to your portfolio, because it is.

## Your profile page
- **Pin 4–6 repos** — your best work, not your most recent work
  (Profile → Customize your pins)
- **Add a profile README** — create a repo with the exact same name as
  your username, public, with a `README.md` — it renders on your profile
  page automatically. Keep it short: who you are, what you're learning,
  links to your best work
- **Fill out your bio, location, and a link** (portfolio site or LinkedIn)

## What makes a repo's README good
This is the single highest-leverage thing you can improve. A visitor
decides whether to look closer within the first screen. At minimum:
1. **A one-line description** at the top — what it does and who it's for
2. **A screenshot or GIF** if it has any visual output — people skim
   images before they read text
3. **A quick-start section** — how to run it, in as few steps as possible
4. **What you'd do differently** — a short, honest note (shows
   self-awareness and growth, which reads well to reviewers)

## Commit hygiene
- Write commit messages that describe *what changed and why*, not
  `update`, `fix`, `asdf`
- Use specific `git add <file>` instead of `git add .` where it matters,
  to avoid committing things you didn't mean to
- Don't squash your entire project into one commit — a visible history
  of incremental progress is a positive signal, not something to hide

## Repo hygiene checklist
- [ ] A license file (MIT is a sensible default for personal projects)
- [ ] A `.gitignore` appropriate to your language/framework (no
      `node_modules`, no `.env` files with secrets, no compiled binaries)
- [ ] No secrets or API keys committed, ever — use environment variables
- [ ] Topics/tags added to the repo (Settings → Topics) so it's discoverable
- [ ] No dead links or empty sections in the README

## Contribution activity
The green squares matter less than people think — a graph full of
one-line commits to pad activity is easy to spot and doesn't help you.
Genuine, consistent project work naturally produces a reasonable graph
over time. Don't optimize for the graph directly.

## Open source contributions
Even small contributions to other people's projects are a strong
signal:
- Start with issues labeled `good first issue` on repos you actually
  use or find interesting
- Read the project's `CONTRIBUTING.md` before opening a PR
- A merged one-line documentation fix is a completely legitimate first
  contribution — the goal is learning the workflow, not the size of the change

## What NOT to do
- Don't fork a popular repo and claim it as your own work
- Don't fill your profile with 30 half-finished repos — archive or
  delete abandoned experiments, or at least unpin them
- Don't buy stars, followers, or contributions — it's detectable and
  damages credibility more than having zero would
