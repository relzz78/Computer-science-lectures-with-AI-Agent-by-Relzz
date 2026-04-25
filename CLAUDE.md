# CLAUDE.md

This file provides guidance to [Claude Code](https://claude.com/claude-code) (and other AI coding agents) when working with code in this repository.

## Project Overview

**Computer Science Lectures with AI Agent by Relzz** (originally *Kuliah Komputer Sciences with AI Agent by Relzz*) is a learning-focused repository for computer science lecture material, prepared with the assistance of AI agents. The repository is in an early stage and primarily contains documentation and lecture notes.

The working language for lecture content may be a mix of **Indonesian** and **English**. Preserve the original language of any existing notes when editing them.

## Repository Structure

The repository is currently minimal:

- `README.md` — top-level project description.
- `CLAUDE.md` — this file; instructions for AI agents.

As the project grows, lecture material is expected to be organized by topic (e.g. `algorithms/`, `data-structures/`, `operating-systems/`) with notes in Markdown and any code samples kept alongside the relevant lecture.

## Conventions

- **Documentation:** Markdown (`.md`). Use clear headings, short paragraphs, and code fences with language tags for any code snippets.
- **Filenames:** Use lowercase with hyphens (e.g. `binary-search-trees.md`) for new lecture notes.
- **Language:** Match the surrounding content. If a folder's existing notes are in Indonesian, write new notes in Indonesian; otherwise use English.
- **Code samples:** Keep small, runnable, and self-contained. Prefer the language already used in nearby lectures.

## Working Guidelines for AI Agents

- Make **minimal, focused changes**. Do not refactor or reorganize existing files unless explicitly requested.
- Do not invent project structure — if a directory does not exist yet, ask before creating large scaffolding.
- Preserve the author's voice and any pedagogical framing in lecture notes.
- Never commit secrets, API keys, or personal data.
- When adding new lecture material, include a brief summary at the top and, where helpful, a list of references at the bottom.

## Common Tasks

- **Add a new lecture note:** Create a Markdown file in the appropriate topic folder (or propose a folder if none fits) with a title, summary, body, and references section.
- **Fix typos / improve clarity:** Edit in place; keep changes scoped to the requested file.
- **Add code examples:** Place inline in the relevant note using fenced code blocks; for longer programs, add a sibling file and link to it from the note.

## Git & PR Workflow

- Branch from `main` using a descriptive branch name.
- Keep commits focused and write clear commit messages.
- Open a pull request describing what was added or changed and why.
