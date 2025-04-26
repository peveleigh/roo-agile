### Output Format

```markdown story template
# Story {N}: {Title}

## Story

**As a** {role}\
**I want** {action}\
**so that** {benefit}.

## Status

Draft OR In-Progress OR Complete

## Context

{A paragraph explaining the background, current state, and why this story is needed. Include any relevant technical context or business drivers.}

## Estimation

Story Points: {Story Points (1 SP=1 day of Human Development, or 10 minutes of AI development)}

## Acceptance Criteria

1. - [ ] {First criterion - ordered by logical progression}
2. - [ ] {Second criterion}
3. - [ ] {Third criterion}
         {Use - [x] for completed items}

## Subtasks

1. - [ ] {Major Task Group 1}
   1. - [ ] {Subtask}
   2. - [ ] {Subtask}
   3. - [ ] {Subtask}
2. - [ ] {Major Task Group 2}
   1. - [ ] {Subtask}
   2. - [ ] {Subtask}
   3. - [ ] {Subtask}
            {Use - [x] for completed items, - [-] for skipped/cancelled items}

## Testing Requirements:\*\*

    - Reiterate the required code coverage percentage (e.g., >= 85%).

## Story Wrap Up (To be filled in AFTER agent execution):\*\*

- **Agent Model Used:** `<Agent Model Name/Version>`
- **Agent Credit or Cost:** `<Cost/Credits Consumed>`
- **Date/Time Completed:** `<Timestamp>`
- **Commit Hash:** `<Git Commit Hash of resulting code>`
- **Change Log**
  - change X
  - change Y
    ...
```