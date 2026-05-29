<div align="center">

# Agent Skill Catalog

Reusable Codex skills for consistent AI-assisted engineering workflows.

</div>

<p align="center">
  <img src="https://img.shields.io/badge/Status-In%20Progress-F59E0B?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Type-Agent%20Skills-8B5CF6?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Focus-Documentation%20Systems-58A6FF?style=for-the-badge" />
</p>

<div align="center">

**Nicolas AI Engineering Lab**<br>
AI Engineering - Software Architecture - Cloud - Agent Systems

</div>

## Overview

This repository stores reusable Codex skills that can be installed globally and used across multiple projects.

## Highlights

<table>
<tr>
<td width="50%">

### Reusable Skills

Each skill is a standalone folder with its own `SKILL.md`, metadata, references, and optional assets.

</td>
<td width="50%">

### Consistent Documentation

The README design system keeps repository presentation aligned across the portfolio.

</td>
</tr>
</table>

## Architecture

```mermaid
flowchart TD
    A[Skill Repository] --> B[skills/]
    B --> C[readme-design-system]
    C --> D[SKILL.md]
    C --> E[references/]
    C -. symlink .-> F[~/.codex/skills]
    F --> G[Any Codex Project]
```

## Before vs After

| Before | After |
|---|---|
| Scattered prompts | Versioned skill system |
| Flat READMEs | Visual technical landing pages |
| Manual repetition | Reusable documentation framework |

## Author

Built by **Nicolas Hoyos**<br>

Software Engineering - AI Engineering - Software Architecture<br>

> Building intelligent systems, scalable architectures, and practical AI products.
