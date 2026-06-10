# Contribution [#6814]: Bitbucket-Pull-Requests: Add Bitbucket Cloud support

**Contribution Number:** [1]  
**Student:** Joo An Choi 
**Issue:** [[GitHub issue link]](https://github.com/backstage/community-plugins/issues/6814)
**Status:** Phase I

---

## Why I Chose This Issue

This issue caught my attention because it seems like resolving this issue would have a lot of impact. Bitbucket cloud is used by thousands of orgs. Foxing this issue would allow their cloud version control tool to be aligned with their developer dashboard. I think it's a good experience to have, especially for an internal tools team. 

I've worked with JS so working with Typescript should not require much ramp-up. I think the issue is also a good way to learn about Backup plugin system. I think it would be fun to think about mapping API JSON payloads into front end interfaces. It's similar work to what I have done and working with it to ensure backwards compatibility could be a fun challenge.

---

## Understanding the Issue

### Problem Description

The Backstage Bitbucket Pull Requests plugin currently lacks integration with Bitbucket Cloud so it cannot fetch or display pull request data using the Cloud version due to its distinct REST API.

### Expected Behavior

The plugin can seamlessly detect a user's Bitbucket environment via the app-config.yaml file and use a dedicated API client to populate the existing Backstage UI components with Bitbucket Cloud PR data

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
