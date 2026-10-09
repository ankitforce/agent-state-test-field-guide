# Agent State Test Checklist

- [ ] The workflow has a clear task objective.
- [ ] The starting state is captured or reproducible.
- [ ] The expected terminal state is defined.
- [ ] Required field changes are listed.
- [ ] Fields that must not change are listed.
- [ ] Required side effects are listed.
- [ ] Forbidden side effects are listed.
- [ ] The agent has only the tools needed for the task.
- [ ] Each state-changing tool call is logged.
- [ ] Executable checks compare expected and actual state.
- [ ] Evidence links are retained.
- [ ] Human approvals are recorded where needed.
- [ ] The workflow is repeated enough times to catch inconsistency.
- [ ] The completion receipt records pass or fail.
