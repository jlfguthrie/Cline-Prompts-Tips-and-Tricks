# Prompt examples

Adapt these examples to the codebase and the change you need. They describe a workflow; they do not guarantee a particular result or replace review.

## Understand a project

```text
Help me understand this project before making changes.
Read the relevant entry points, configuration and existing documentation.
Summarise its purpose, main components and how they interact.
Identify the commands used to build and verify it.
Separate confirmed findings from assumptions. Do not modify files yet.
```

## Implement a feature

```text
Implement: [FEATURE AND EXPECTED BEHAVIOUR]

Read the relevant code and project instructions first.
Identify the affected data, APIs and interface behaviour.
Follow the existing patterns and keep the change scoped to the requirement.
Check important edge cases and run the relevant verification.
Summarise the change, what was checked and any remaining limits.
```

## Debug a problem

```text
Investigate: [SYMPTOM, EXPECTED BEHAVIOUR AND REPRODUCTION STEPS]

Gather the relevant logs, code paths and recent changes.
Use the evidence to identify likely causes and test them with focused checks.
Explain the cause before changing the implementation.
Make a scoped fix and verify the original reproduction case.
```

## Review a change

```text
Review: [DIFF, COMMIT OR PULL REQUEST]

Check correctness, edge cases, data handling and compatibility with callers.
Read enough surrounding code to understand the affected behaviour.
Report actionable issues with file references and an explanation of the impact.
Distinguish confirmed defects from questions. Do not modify files.
```

## Build an API endpoint

```text
Add an endpoint for: [USE CASE]

Follow the project's existing API conventions.
Define the request, response, validation and authorisation requirements.
Consider errors, retries and pagination where relevant.
Implement the endpoint and verify its callers and failure cases.
Document the behaviour needed by someone integrating with it.
```

## Build an interface component

```text
Build: [COMPONENT, USERS AND REQUIRED INTERACTIONS]

Use the existing design system and component patterns.
Define the input, loading, empty and error states that apply.
Check keyboard access, responsive layout and integration with the data source.
Verify the resulting behaviour in the interface.
```

## Refactor existing code

```text
Refactor: [COMPONENT AND REASON]

Describe the current contract and the behaviour that must be preserved.
Keep unrelated functionality outside the change.
Use existing verification to check behaviour before and after the refactor.
Explain any changes callers need to make.
```

## Maintain project context

```text
Review the project notes against the work just completed.
Identify outdated facts, useful decisions and repeatable commands.
Update only the relevant documentation, retaining the reason for each decision.
Do not copy credentials, customer records or temporary output into shared notes.
```

## Examine a problem from several perspectives

```text
Consider: [PROBLEM]

Examine the requirements, implementation, review and verification needs.
Identify conflicts between those perspectives and explain the tradeoffs.
Keep conclusions grounded in the same code and requirements.
```

## Plan a gradual rollout

```text
Plan a rollout for: [CHANGE]

Assess whether a feature flag or staged release is useful for this change.
Identify dependencies, verification, monitoring and rollback needs.
If a temporary flag is appropriate, define how and when it will be removed.
```

## Contributing an example

Include the task it addresses, the context it needs and any limitations you observed. Link supporting files that exist in the repository.
