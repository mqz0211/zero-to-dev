# Linux & The Command Line

> "Just learn Linux" is the most common — and least explained — advice
> given to new developers. Here's what it actually means and why.

## What is Linux, really?

Linux is a **free, open-source operating system** — an alternative to
Windows or macOS. But it's also something bigger: a philosophy and an
ecosystem. Almost every server on the internet, every cloud platform
(AWS, Google Cloud, Azure), and most developer tools are built to run
on Linux first.

**Why it matters for you:** if you become a software engineer,
cybersecurity specialist, or cloud engineer, you will use Linux
*constantly* — not because it's trendy, but because that's where the
industry actually runs.

## What is "the command line"?

The command line (also called a terminal, shell, or CLI) is a
text-based way of controlling your computer — instead of clicking
icons, you type instructions. It looks intimidating at first and
becomes the fastest way to work once it clicks.

```bash
$ ls
Desktop  Documents  Downloads  Projects

$ cd Projects
$ mkdir my-first-repo
$ cd my-first-repo
```

That's: "list what's here," "go into Projects," "make a new folder,"
"go into it." That's genuinely most of what you need to get moving.

## The 15 commands that cover 90% of daily use

| Command | What it does |
|---|---|
| `pwd` | Print where you currently are |
| `ls` | List files in the current folder |
| `cd <folder>` | Move into a folder |
| `cd ..` | Move up one folder |
| `mkdir <name>` | Make a new folder |
| `touch <file>` | Create an empty file |
| `rm <file>` | Delete a file (careful — no trash bin!) |
| `rm -r <folder>` | Delete a folder and everything in it |
| `cp <a> <b>` | Copy a file |
| `mv <a> <b>` | Move or rename a file |
| `cat <file>` | Print a file's contents |
| `grep "text" <file>` | Search for text inside a file |
| `chmod +x <file>` | Make a file executable |
| `sudo <command>` | Run a command as administrator |
| `man <command>` | Show the manual for any command |

## Why developers "live" in the terminal

- **Speed:** typing `git commit -m "fix bug"` is faster than five mouse clicks.
- **Automation:** you can chain commands into scripts that run themselves.
- **It's how servers work:** most servers have no visual interface at
  all — the terminal *is* the interface.
- **It's universal:** the same commands work whether you're on your
  laptop or a cloud server on the other side of the world.

## You don't need to install Linux to start

You can practice Linux commands right now:
- **macOS:** already has a Unix-based terminal built in (search "Terminal")
- **Windows:** install [WSL (Windows Subsystem for Linux)](https://learn.microsoft.com/windows/wsl/install) — a real Linux environment inside Windows
- **Browser-based:** try an in-browser Linux sandbox with zero install

## ✅ Check yourself

You're ready to move on when you can, without looking anything up:
- Navigate into a folder three levels deep and back out
- Create a folder, create a file inside it, then delete both
- Explain what `sudo` does and why you should be careful with it

## Next steps

- [`networking.md`](networking.md) — what happens when you type a URL and hit enter
- [Beginner projects](../PROJECTS/beginner-projects.md) — several assume basic command-line comfort
- If cybersecurity interests you, the [Cybersecurity roadmap](../ROADMAPS/cybersecurity.md) goes much deeper on Linux
