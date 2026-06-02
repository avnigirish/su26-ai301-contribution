# Contribution [#]: docs(monitoring): narrow PlotLossPerTimestep typing + docstring to surface flow-matching coupling

**Contribution Number:** [1 / 2 / 3]  
**Student:** Avni Girish  
**Issue:** https://github.com/tinaudio/synth-setter/issues/653  
**Status:** Phase I Complete

---

## Why I Chose This Issue

I chose this issue because it is a well-scoped, self-contained task that lives entirely in a single file (`src/utils/callbacks.py`) and focuses on type annotations and documentation rather than changing runtime behavior. It's labeled `good first issue`, comes with exact file and line references, and even includes the maintainer's own explanation of *why* per-timestep loss matters — so there's plenty of context to move quickly without guessing.

It also matches my skills and learning goals well. I'm comfortable with Python and type hints, and this issue lets me ramp up on a real ML codebase (PyTorch Lightning, Hydra, Pydantic) in a low-risk way: I have to understand enough of the flow-matching context to document it accurately, but I don't have to implement model logic. I hope to learn how a research-grade training project is structured, how its callbacks and modules fit together, and how to write a clean, reviewable contribution that follows the project's conventions.

---

## Understanding the Issue

### Problem Description

[In your own words, what's broken or missing?]

### Expected Behavior

[What should happen?]

### Current Behavior

[What actually happens?]

### Affected Components

[Which parts of the codebase are involved?]

---

## Reproduction Process

### Environment Setup

[Notes on setting up your local development environment - challenges you faced, how you solved them]

### Steps to Reproduce

1. [Step 1]
2. [Step 2]
3. [Observed result]

### Reproduction Evidence

- **Commit showing reproduction:** [Link to commit in your fork]
- **Screenshots/logs:** [If applicable]
- **My findings:** [What you discovered during reproduction]

---

## Solution Approach

### Analysis

[Your analysis of the root cause - what's causing the issue?]

### Proposed Solution

[High-level description of your fix approach]

### Implementation Plan

Using UMPIRE framework (adapted):

**Understand:** [Restate the problem]

**Match:** [What similar patterns/solutions exist in the codebase?]

**Plan:** [Step-by-step implementation plan]
1. [Modify file X to do Y]
2. [Add function Z]
3. [Update tests]

**Implement:** [Link to your branch/commits as you work]

**Review:** [Self-review checklist - does it follow the project's contribution guidelines?]

**Evaluate:** [How will you verify it works?]

---

## Testing Strategy

### Unit Tests

- [ ] Test case 1: [Description]
- [ ] Test case 2: [Description]
- [ ] Test case 3: [Description]

### Integration Tests

- [ ] Integration scenario 1
- [ ] Integration scenario 2

### Manual Testing

[What you tested manually and results]

---

## Implementation Notes

### Week [X] Progress

[What you built this week, challenges faced, decisions made]

### Week [Y] Progress

[Continue documenting as you work]

### Code Changes

- **Files modified:** [List]
- **Key commits:** [Links to important commits]
- **Approach decisions:** [Why you chose certain approaches]

---

## Pull Request

**PR Link:** [GitHub PR URL when submitted]

**PR Description:** [Draft or final PR description - much of the content above can be adapted]

**Maintainer Feedback:**
- [Date]: [Summary of feedback received]
- [Date]: [How you addressed it]

**Status:** [Awaiting review / Iterating / Approved / Merged]

---

## Learnings & Reflections

### Technical Skills Gained

[What you learned technically]

### Challenges Overcome

[What was hard and how you solved it]

### What I'd Do Differently Next Time

[Reflection on your process]

---

## Resources Used

- [Link to helpful documentation]
- [Tutorial or Stack Overflow post that helped]
- [GitHub issues or discussions that helped]
