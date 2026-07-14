# Networking, APIs & The Internet

> What actually happens when you type a URL and hit enter? What is an
> "API"? This file demystifies the words developers use constantly and
> rarely explain.

## What happens when you visit a website

1. You type `example.com` and hit enter.
2. Your computer asks a **DNS server** (think: phonebook for the
   internet) "what's the address for example.com?" and gets back an
   **IP address** like `93.184.216.34`.
3. Your computer sends a request to that address, asking for the
   webpage.
4. A **server** — just another computer, usually far away, always on —
   receives that request and sends back the webpage's data.
5. Your **browser** turns that data into the page you see.

This entire round trip usually takes well under a second.

## Client vs. server

- **Client:** the device requesting something (your laptop, your phone)
- **Server:** the device responding to that request (usually a
  computer running 24/7 somewhere in a data center)

Almost every app you use is a conversation between a client and a
server. Learning to build software professionally means learning to
build one or both sides of that conversation.

## What is an API?

**API** stands for Application Programming Interface. Strip away the
jargon: an API is just **a defined way for two pieces of software to
talk to each other** — a menu of requests one program can make to
another, and the responses it'll get back.

**Real-world analogy:** a restaurant menu is an API. You don't need to
know how the kitchen works — you just need to know what you're allowed
to order (the available requests) and what you'll get back (the
response).

**Example:** a weather app doesn't calculate weather itself — it sends
a request to a weather API ("give me today's forecast for this city")
and displays whatever comes back.

## HTTP — the language of the web

**HTTP** (HyperText Transfer Protocol) is the set of rules clients and
servers use to talk to each other. The most common request types:

| Method | Meaning | Example |
|---|---|---|
| `GET` | "Give me data" | Load a webpage |
| `POST` | "Here's new data, save it" | Submit a sign-up form |
| `PUT`/`PATCH` | "Update this existing data" | Edit your profile |
| `DELETE` | "Remove this data" | Delete a post |

You've also seen **status codes** without knowing what they meant:
`200` = success, `404` = not found, `500` = server error.

## What is "the cloud"?

"The cloud" is not magic — it's **someone else's computer**, running
in a data center, that you rent access to instead of buying and
maintaining hardware yourself. When you hear "deployed to AWS" or
"hosted on the cloud," it means: the code is running on a server owned
by a cloud provider (Amazon, Google, Microsoft), not on a physical
machine sitting under someone's desk.

## Ports, in one sentence

If an IP address is a building's street address, a **port** is the
specific door/apartment number — it lets one machine run many
different services (a website on port 80, a database on port 5432)
without them interfering with each other.

## ✅ Check yourself

You're ready to move on when you can explain, in your own words:
- The difference between a client and a server
- What an API actually is, using a non-technical analogy
- What `GET` and `POST` are each typically used for

## Next steps

- [`problem-solving.md`](problem-solving.md) — how developers actually think through problems
- [Beginner projects](../PROJECTS/beginner-projects.md) — several projects have you call a real API
- [Web Developer roadmap](../ROADMAPS/web-developer.md) goes deep on client/server architecture
