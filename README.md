# Vibe Coding Scripts - SharePoint Embedded (SPE)

This was written by GHCP with my input.  Last update 2025-04-07.

## General Advice for Working with AI Coding Assistants

When working with AI coding assistants, keep these tips in mind:

* **Non-deterministic responses**: LLMs are non-deterministic by nature, so you'll likely get different results than shown in these examples each time you run the same prompt.

* **Break down your requests**: The core strategy with AI coding assistants is to break your instructions into manageable chunks and build on them incrementally, testing frequently.

* **Restart when stuck**: Sometimes these assistants can get into non-productive loops. If this happens, the best approach is often to find a way to start over with a fresh prompt.

## Comparative Analysis of AI Coding Assistants

Based on my experience with these tools:

* **Lovable**: Great for quickly prototyping greenfield solutions where you're starting from scratch.

* **GitHub Copilot** (Insiders edition with Agent workflow): Best suited for working with existing codebases where understanding context is important.

* **Cursor**: Positions itself between the two, offering a balance of prototyping capabilities and contextual awareness.

## Repository Structure

This repository is organized into separate folders for each AI coding assistant:

```
├── cursor/
│   ├── part1-foundation.txt
│   ├── part2-containers-and-files.txt
│   └── part3-search.txt
│
├── github-copilot/
│   ├── part1-foundation.txt
│   ├── part2-containers.txt
│   └── part3-files.txt
│
└── lovable/
    ├── part1-foundations.txt
    ├── part2-search.txt
    ├── part3-container-perms.txt
    ├── part4-delete.txt
    └── part5-dev-mode.txt
```

Each folder contains text files that demonstrate different aspects of working with SharePoint Embedded using the respective AI coding assistant. The files are organized in a progressive manner, starting with foundational concepts and building toward more advanced functionality.

## Contents

This repository contains scripts and examples demonstrating the use of various AI coding assistants with SharePoint Embedded (SPE). The examples cover topics such as:

- Setting up basic foundations for SPE work
- Working with containers and file operations
- Implementing search functionality
- Managing container permissions
- Deletion operations
- Development mode utilization


