# Contributing to Awesome Terminal Games

Thank you for your interest in contributing!

## How to Add a Game

1. Edit `games.toml` and add a new `[[games]]` entry
2. Follow the schema below
3. Submit a pull request

## Game Entry Schema

```toml
[[games]]
name = "Game Name"
category = "arcade"           # arcade | puzzle | roguelike | strategy | board | card | other
tier = "native"               # native | msys2 | cross-platform | python | web
github = "owner/repo"         # GitHub repo (preferred) OR url
url = "https://..."           # Website (if no GitHub)
license = "MIT"
language = "C"
description = "Short description of the game"
tags = ["tag1", "tag2"]
```

## Tier Definitions

| Tier | Meaning | Install Method |
|------|---------|----------------|
| `native` | Prebuilt Windows .exe or zero-dependency ANSI | Direct download |
| `msys2` | Needs MSYS2/MinGW to compile | Build command provided |
| `cross-platform` | Rust/Go with cross-platform builds | `cargo install` or download |
| `python` | Python package | `pip install` |
| `web` | Playable in browser | URL provided |

## Rules

- Game must be open source or free to play
- Game must run in a terminal (not GUI)
- One entry per game (no duplicates)
- Keep descriptions concise (one sentence)
- Alphabetical ordering within categories

## Code of Conduct

Be respectful and constructive. We're here to celebrate terminal games together.
