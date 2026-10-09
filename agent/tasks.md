# Agent Tasks

## Draft A State-Test Plan

Given a workflow description, produce:

- expected terminal state
- starting state reference
- required side effects
- forbidden side effects
- executable checks
- evidence to retain
- human approval points

## Review A Workflow

Given an agent workflow, identify:

- ambiguous task objective
- missing durable state checks
- unbounded tool authority
- side effects that are not audited
- repeatability gaps
- completion claims without evidence

## Produce Completion Evidence

Given observed run data, create a JSON record using `schemas/completion-evidence.schema.json`.
