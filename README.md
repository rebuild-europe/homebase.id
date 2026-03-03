# Homebase.id

ｈｏｍｅｂａｓｅ．ｉｄ

**Your home on the Internet** — a fully distributed, self-sovereign platform for private communications, secure storage, personal social networking, web presence, and self-sovereign identity management (with SSO, verification, digital signatures). Everything is owned and controlled by *you*. Most importantly Homebase is an App Platform that allows anyone to write decentralized privacy focused secure apps with little effort.

Your identity is simply a domain name (e.g. `yourname.dotyou.cloud`) - you can even get one for free. There is no central company, no single server farm, and no gatekeeper controlling the network, and can be hosted anywhere, even on your kitchen table, and yet it's unlike other decentralized system it's working just as simply as any other App you're used to and fully based on open Internet standards.

Homebase is currently in **Alpha** (invitation-only for the hosted version - the passphrase for Rebuild.net is: rebuild ). This repository submission for **Rebuild.net** includes the core infrastructure plus working prototypes for key social features (Chat with Signal-like UX, Feed, Photos, etc.). All is available as open-source FLOSS AGPL3.

**Why this fits Rebuild.net**: Homebase offers a complete decentralized alternative to today’s centralized social platforms — privacy-first, user-owned data, interoperable apps, and optional self-hosting. Perfect for the next generation of (European) self-sovereign social platforms.

## Key Features

- Fully distributed network (nobody controls it)
- Self-sovereign identity (your identity = your domain)
- End-to-end encrypted private messaging & storage
- Personal social feed & network (only people you trust)
- Web presence tools: link-tree, personal homepage, bio, CV, blog
- Built-in app platform (Chat, Feed, Photos, Mail, Link Tree, Communities…)
- YouAuth — federated authentication (more secure peer to peer version of OAuth)
- Optional at-home “table-top” hosting
- Everything is fully encrypted at rest and in transit
- Open-source (AGPL-3.0) FLOSS

## Repository Overview

| Repo                                                      | Language   | Purpose 
|-----------------------------------------------------------|------------|---------
| **[homebase-id](https://github.com/homebase-id)**         | —          | Organization root
| **[odin-core](https://github.com/homebase-id/odin-core)** | C# (.NET)  | Backend server
| **[odin-js](https://github.com/homebase-id/odin-js)**     | TypeScript | Monorepo with common web apps (Feed, Chat, Mail) + reusable JS/UI libraries
| **[chat-kmp](https://github.com/homebase-id/chat-kmp)**   | Kotlin KMP | Signal-style UX chat prototype (Android, iOS, Desktop, Web/Wasm)
| **[photo-app](https://github.com/homebase-id/photo-app)** | TypeScript + RN | Rough photo library prototype (mobile + web)

## Quick Start — Run Everything Locally

### 1a. Try it out.
Go to https://homebase.id/
Sign-up
use the pass-phrase: rebuild

Search for Homebase.id on the App-store (previous generation Chat app, soon to be replaced with the one above)

### 1b. Get the code (Odin-Core)

Go to the repos above, at a minimum get odin-core and odin-js
Follow the README.md instructions for each.

Runs on Linux, Mac, Windows.
