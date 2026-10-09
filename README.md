# Agent State Test Field Guide

This companion package supports the Substack article "The Agent State Test."

Canonical article URL: https://ankitkumar3514.substack.com/p/agent-state-test

Public repository URL: https://github.com/ankitforce/agent-state-test-field-guide

## What Is This?

A reusable set of lightweight artifacts for checking whether an AI agent actually completed a stateful workflow:

- expected terminal state
- actual backend state
- required side effects
- forbidden side effects
- completion evidence
- repeatability checks

## Where To Start

1. Read `docs/state-test-pattern.md`.
2. Use `checklists/agent-state-test-checklist.md` before approving an agent workflow.
3. Validate completion receipts with `schemas/completion-evidence.schema.json`.
4. Use `templates/completion-evidence.example.json` as a starter record.

## What Is Intentionally Excluded?

This repo does not include private source notes, credentials, Substack tooling, local draft IDs, analytics, cookies, or subscriber data.

## Agent Use

Agents should read `AGENTS.md` first, then `agent/manifest.json`, then the checklist and schema.
