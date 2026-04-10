# Seedlay CLI

The autonomous seed client for Seedlay — a zero-trust agentic runtime.

---

> 🚀 Seedlay is currently onboarding early users in limited batches.

## What is Seedlay CLI?

Seedlay CLI is the local runtime for the Seedlay platform.

It connects your local/cloud project environment to Seedlay Hub and enables execution, monitoring, and agent interaction.

Seedlay combines:
- a **dashboard** for visibility, orchestration, and control
- a **CLI runtime** for local execution and project-level connectivity

Define a mission — Seedlay handles execution and improves over time.

---

## Early Access

Seedlay is currently in closed testing.

New users can request access through the signup form at [seedlay.com](https://seedlay.com).  
Approved users may be invited into limited testing batches as the platform is validated and expanded.

---

## How Access Works

To use Seedlay:

1. Sign up at [seedlay.com](https://seedlay.com)
2. Join the early access list
3. Receive approval for closed testing
4. Install the Seedlay CLI
5. Connect your local project to Seedlay Hub

> Access to the CLI and platform functionality is currently limited to approved testers.

---

## Installation

Install the Seedlay CLI globally with npm:

```bash
npm install -g seedlay
```

---

## Requirements

- Node.js 18 or later

---

## Quick Start

```bash
# Initialize a new project
seedlay init

# Connect to Seedlay Hub
seedlay connect

# Check status
seedlay status
```

> Note: Full functionality requires access to the Seedlay platform and Seedlay Hub.

---

## Commands

| Command | Description |
|---------|-------------|
| `seedlay init` | Initialize a new project directory |
| `seedlay connect` | Connect to Seedlay Hub and run as a background daemon |
| `seedlay connect -f` | Connect in foreground mode |
| `seedlay stop` | Stop the background daemon |
| `seedlay status` | Show connection and sandbox status |
| `seedlay logs` | View recent activity logs |
| `seedlay logs -f` | Follow logs in real time |
| `seedlay sandbox` | Show sandbox disk usage |
| `seedlay architect <cmd>` | Send a command to the Architect AI |

---

## Core Principles

Seedlay is designed around a few core principles:

- **Autonomous execution** — agents can carry out tasks and workflows with minimal manual overhead
- **Evolving systems** — execution improves over time through iteration, feedback, and learning loops
- **Built to help build** — Seedlay is designed to support project creation, extension, and ongoing software execution
- **Zero-trust architecture** — security boundaries and permission-aware execution are built into the system design
- **Human-in-the-loop when needed** — automation does not remove oversight; users can stay in control of key decisions
- **Full control** — users decide how much autonomy, visibility, and intervention they want

---

## How Seedlay Works

1. Initialize your project with the CLI
2. Connect your environment to Seedlay Hub
3. Manage visibility and orchestration through the Seedlay dashboard
4. Execute missions through the runtime
5. Let the system adapt and improve over time

Seedlay is not just automation — it is an evolving execution system.

---

## Status

Early development. Limited access.

Interfaces, commands, and capabilities may evolve during closed testing.

---

## License

Licensed. All rights reserved.
