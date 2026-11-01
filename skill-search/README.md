# Skill Search

A Codex skill for finding skills on GitHub. Describe what you need, and it searches for relevant repositories and explains why they may be useful.

## How it works

The skill turns your request into search queries, uses AnySearch to find results, and deduplicates the matching repositories. See [SKILL.md](./SKILL.md) for the full workflow.

## Installation

Ask Codex to install the `skill-search` skill from `par73e/skill-searcher`.

## Example requests

- “Find a skill for working with PDFs.”
- “Search for a skill that can create presentations.”
- “Is there a skill for analyzing spreadsheets?”

## Requirements

The search workflow uses AnySearch.
