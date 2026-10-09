# State-Test Pattern

An agent state test verifies a workflow by checking durable system state, required side effects, forbidden side effects, and repeatability.

## Pattern

1. Define the task objective.
2. Capture the starting state reference.
3. Define the expected terminal state.
4. Limit the tools available to the agent.
5. Run the task.
6. Check the actual terminal state.
7. Check required side effects.
8. Check forbidden side effects.
9. Repeat from a clean starting state.
10. Write a completion receipt.

## Why It Matters

Tool calls are useful evidence, but they are not enough. A trace can look correct while the database, ticket, account, file, or policy record remains wrong.

## Good State Tests

- map to durable records
- are executable
- distinguish required and forbidden effects
- preserve evidence links
- include repeatability criteria
- produce a pass/fail result

## Weak State Tests

- only inspect final text
- only count successful tool calls
- rely on subjective review
- omit forbidden side effects
- cannot be rerun from a clean fixture
