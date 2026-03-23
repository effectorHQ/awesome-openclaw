# Awesome OpenClaw

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](./CONTRIBUTING.md) [![CC0](https://img.shields.io/badge/license-CC0%201.0-lightgray.svg)](https://creativecommons.org/publicdomain/zero/1.0/) [![Skills](https://img.shields.io/badge/3286%2B%20skills-on%20ClawHub-E03E3E)](https://clawhub.com)

A curated list of high-quality resources, skills, extensions, and tools for the OpenClaw ecosystem and proactive AI development.

**What is this?** An editorial guide to the best OpenClaw skills and complementary technologies. While [ClawHub](https://clawhub.com) is the machine-searchable registry where skills are published and discovered, this list highlights curated recommendations, organized by use case, with context on why each project is valuable.

> Contributions welcome. See [Contributing](#contributing) for submission guidelines.

---

## Contents

- [OpenClaw Ecosystem](#openclaw-ecosystem)
- [Skills by Category](#skills-by-category)
  - [Developer Tools](#developer-tools)
  - [Communication](#communication)
  - [Productivity](#productivity)
  - [DevOps & Infrastructure](#devops--infrastructure)
  - [Data & Analytics](#data--analytics)
- [Extensions](#extensions)
- [Frameworks & Libraries](#frameworks--libraries)
- [Learning Resources](#learning-resources)
- [Community Projects](#community-projects)
- [Contributing](#contributing)
- [License](#license)

---

## OpenClaw Ecosystem

Core projects and official resources:

- [OpenClaw](https://github.com/openclaw/openclaw) — The main TypeScript/Node.js runtime. Hands for AI that move first.
- [ClawHub](https://clawhub.com) — Official skill registry with vector search, publish/install/sync capabilities.
- [Lobster](https://github.com/effectorHQ/lobster) — Agent orchestration framework for multi-step workflows.
- [ACPX](https://github.com/effectorHQ/acpx) — AI Composition Protocol for skill composition and chaining.
- [plugin-template](https://github.com/effectorHQ/plugin-template) — Official template for creating new OpenClaw skills.
- [skill-lint](https://github.com/effectorHQ/skill-lint) — CLI linter for SKILL.md files. Catches errors before `clawhub publish`.
- [skill-lint-action](https://github.com/effectorHQ/skill-lint-action) — GitHub Action wrapping skill-lint. Inline PR annotations, job summaries, zero config. Add to any skill repo in one step.

---

## Skills by Category

Official and community-maintained skills, organized by use case. Install via: `openclaw plugins install <name>`

### Developer Tools

Skills for code, version control, and development workflows.

- **github** — Interact with GitHub repositories, issues, pull requests, and workflows. Automate code review, create releases, and manage CI/CD from within OpenClaw.
- **git** — Advanced Git operations: branching, rebasing, cherry-picking, worktrees. Essential for complex version control workflows.
- **git-worktree** — Dedicated skill for Git worktree management. Create and manage isolated branches for parallel development.
- **docker-manager** — Build, run, and manage Docker containers and images. Push to registries and orchestrate containerized workloads.
- **shell** — Execute shell commands and scripts. Useful for system operations, installations, and custom workflows.

### Communication

Connect OpenClaw to messaging and collaboration platforms.

- **slack** — Post messages, create threads, manage channels, and respond to events in Slack workspaces.
- **discord** — Send messages and interact with Discord servers. Integrate OpenClaw agents into community servers.
- **telegram** — Send and receive messages via Telegram bots. Build notification and command workflows.
- **email** — Send emails, read inboxes, and manage attachments. Integrate email workflows into agent operations.

### Productivity

Tools for task management, scheduling, and information management.

- **notion** — Read and write Notion databases, pages, and blocks. Sync OpenClaw workflows with Notion workspaces.
- **notion-sync** — Specialized skill for syncing large Notion workspaces with OpenClaw data stores.
- **calendar** — Create and manage calendar events. Schedule tasks, meetings, and reminders.
- **todoist** — Manage Todoist projects and tasks. Integrate task creation and tracking into agents.
- **airtable** — Interact with Airtable bases and records. Treat Airtable as a lightweight database for OpenClaw.

### DevOps & Infrastructure

Infrastructure automation, containerization, and CI/CD.

- **kubernetes** — Deploy and manage Kubernetes clusters, namespaces, and workloads. Essential for cloud-native operations.
- **terraform** — Infrastructure-as-code operations. Create, update, and destroy cloud resources via Terraform.
- **aws** — AWS services integration. Launch EC2 instances, manage S3, RDS, Lambda, and more.
- **docker-manager** — Container operations: build, push, run, and inspect Docker images and containers.
- **postgres-query** — Execute SQL queries against PostgreSQL databases. Read and transform data.
- **ci-cd** — Generic CI/CD skill for GitHub Actions, GitLab CI, Jenkins, and other platforms.

### Data & Analytics

Data processing, transformation, and analysis.

- **postgres-query** — Execute SQL queries and transformations on PostgreSQL. ETL operations and data analysis.
- **csv** — Parse, transform, and generate CSV files. Useful for data import/export workflows.
- **json** — Transform, validate, and query JSON data. Schema validation and transformation.
- **sql** — Multi-database SQL execution. Works with PostgreSQL, MySQL, SQLite, and more.
- **datadog** — Query metrics and logs from Datadog. Integrate monitoring into OpenClaw agents.
- **api-connector** — Generic HTTP client for REST APIs. Build custom integrations with any web service.

---

## Extensions

Extensions are TypeScript npm packages that add new channels, providers, or runtime capabilities to OpenClaw.

### Official Extensions

- **@effectorhq/slack-provider** — Slack integration for receiving events and commands.
- **@effectorhq/discord-provider** — Discord bot provider for multi-server deployments.
- **@effectorhq/telegram-provider** — Telegram bot provider for secure user access.
- **@effectorhq/http-server** — HTTP server extension for webhook ingestion and REST API exposure.

### Community Extensions

- [OpentheClaw](https://github.com/Jah-yee/OpentheClaw) — SSH tunnel launcher with web-based configuration UI. Zero external dependencies, production-ready.

---

## Frameworks & Libraries

Complementary frameworks and libraries that pair well with OpenClaw for agent development and orchestration.

- [LangChain](https://github.com/langchain-ai/langchain) — The most popular framework for building LLM applications. Integrates with OpenClaw for advanced chain compositions.
- [CrewAI](https://github.com/crewAIInc/crewAI) — Multi-agent orchestration framework. Great for complex, multi-role agent workflows.
- [AutoGen](https://github.com/microsoft/autogen) — Microsoft's multi-agent conversation framework. Native integration with OpenClaw skills.
- [Pydantic AI](https://github.com/pydantic/pydantic-ai) — Type-safe AI agent framework built on Pydantic. Excellent for schema validation.
- [MCP (Model Context Protocol)](https://github.com/modelcontextprotocol) — Open standard for connecting models to tools. Bridges OpenClaw and other AI systems.
- [Anthropic SDK](https://github.com/anthropic-ai/anthropic-sdk-python) — Official Anthropic SDK for Claude API access.
- [Vercel AI SDK](https://github.com/vercel-labs/ai) — TypeScript SDK for building AI applications. Lightweight alternative to LangChain.

---

## Learning Resources

Official documentation, articles, tutorials, and talks on OpenClaw and proactive AI architecture.

### Official Documentation

- [OpenClaw Repository](https://github.com/openclaw/openclaw) — Main project documentation and examples.
- [SKILL.md Specification](https://github.com/openclaw/openclaw/docs/SKILL.md) — Complete format specification for skill files.
- [ClawHub Documentation](https://clawhub.com/docs) — Publishing, discovery, and skill management guide.

### Articles & Research

- [Anthropic: Building effective agents](https://www.anthropic.com/research/building-effective-agents) — Design patterns and best practices for AI agent systems.
- [OpenAI: Function calling guide](https://platform.openai.com/docs/guides/function-calling) — How to connect language models to external tools.
- [Model Context Protocol Spec](https://spec.modelcontextprotocol.io/) — Open standard for tool integration with AI models.

### Community Tutorials

- [Getting Started with OpenClaw](https://github.com/openclaw/openclaw/blob/main/docs/getting-started.md) — Quick start guide for new users.
- [Creating Your First Skill](https://github.com/openclaw/openclaw/blob/main/docs/creating-skills.md) — Step-by-step skill development tutorial.
- [Deploying OpenClaw Agents](https://github.com/openclaw/openclaw/blob/main/docs/deployment.md) — Production deployment patterns.

---

## Community Projects

Projects and experiments built by the effectorHQ community. Ranging from production-ready to experimental. If you have a project to add, please open a PR!

*Be the first to add yours. See [Contributing](#contributing) for details.*

---

## Contributing

To add a project or resource to this list:

### Submission Guidelines

1. **Fork** this repository.
2. **Add your entry** in the appropriate section using this format:
   ```markdown
   - **[project-name](https://github.com/user/project)** — One-sentence description of what it does and why it's valuable.
   ```
3. **Keep descriptions concise** — 1-2 sentences max. Include context on why this belongs in the awesome list.
4. **Open a Pull Request** with a title like "Add: project-name" and briefly explain the contribution.

### Criteria for Inclusion

Projects should meet these standards:

- **Open source or source-available** — Code should be publicly accessible.
- **Relevant to OpenClaw** — Directly integrates with or extends OpenClaw, or enables proactive AI development.
- **Functional** — Not a stub or placeholder. Has demonstrable functionality.
- **Maintained** — Active or recently updated. Projects in early stages are welcome with clear labeling.
- **Quality code** — Well-structured, documented, and follows best practices.

Self-promotion is welcome and encouraged. Be honest about maturity level (alpha, beta, production-ready).

### Ordering

Within each section, entries are listed chronologically (newest last). Sections may reorganize by subcategory as they grow.

---

## License

This project is currently licensed under the [Apache License, Version 2.0](LICENSE.md) 。

This list is licensed under [CC0 1.0 Universal](https://creativecommons.org/publicdomain/zero/1.0/). You are free to use and modify this list for any purpose without attribution.

The projects, skills, and resources linked here retain their own licenses. Please review individual project licenses before use.

---

<sub>Curated by [effectorHQ](https://github.com/effectorHQ). Every effector extends the reach.</sub>
