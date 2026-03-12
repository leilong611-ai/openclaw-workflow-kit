# openclaw-workflow-kit

Practical OpenClaw workflows for knowledge ops, observability, and daily automation.

This repository is the current public home for a small set of OpenClaw components I use in real work.

It focuses on the boring but important part of agent adoption:

- making workflows reusable
- keeping them maintainable
- documenting them clearly
- packaging them for real users instead of one-off demos

## What is inside

### 1. Obsidian sync

Tools for syncing OpenClaw-related Obsidian structures across devices, especially for macOS + iCloud setups.

### 2. Skill observability

Lightweight reporting around recent errors, failed sessions, and estimated API usage costs.

### 3. Cost auditing

Simple helpers for token and spend estimation when operating OpenClaw in daily workflows.

## Why this repo exists

Many AI agent repositories look good in screenshots, but stop at demos.

This repository is different. It is built around practical use:

- knowledge workflows
- daily operations
- multi-device setup
- observability
- cost awareness

My background is in operations, process design, and team management rather than traditional software engineering. That perspective shapes the work here. The goal is not to look clever. The goal is to make AI workflows usable.

## Repository structure

```text
.
├── docs/
├── examples/
├── skills/
│   ├── obsidian-openclaw-sync/
│   ├── openclaw-skill-observability/
│   └── openclaw-cost-auditor/
├── README.md
└── README.zh-CN.md
```

## Start here

- [Chinese overview](README.zh-CN.md)
- [Use cases](docs/use-cases.md)
- [Roadmap](docs/roadmap.md)

## Current focus

- Better public packaging
- Cleaner setup guides
- More real-world examples
- Ongoing maintenance signals

## Who this is for

- OpenClaw users running real daily workflows
- People using Obsidian as part of their AI workflow
- Operators who care about maintainability
- Builders who want practical agent systems instead of novelty demos

## Notes

This repository is being built in public and will evolve in visible, incremental steps.

## License

[MIT](LICENSE)
