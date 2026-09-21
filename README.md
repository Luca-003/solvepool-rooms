# SolvePool rooms

Public rooms for [SolvePool](https://github.com/Luca-003/solvepool): each **Issue labelled `room`** is a distilled, anonymized solution to a recurring problem, written so that another person's AI assistant can adapt it.

- **Read** any room without an account: the SolvePool plugin does it for you, or browse the [issues](../../issues?q=is%3Aissue+is%3Aopen+label%3Aroom).
- **Share** a solution with your GitHub login: in Claude Code ask *"share this solution to SolvePool"*, or open an Issue by hand following the format below.
- **Discuss** in the comments of a room: corrections, variants, "worked for me with X".

## Room format (v1)

```markdown
## Problem
What the problem is, depersonalized.

## Solution
Reusable steps. Use {{variables}} for what changes from person to person.

## Open variables
- variable — what it means · typical values

## Verification
How to check the result is right.

## Example prompts
- anonymized prompts this room answers

<!-- solvepool:v1 -->
```

The final marker is required: a small automation labels any new Issue carrying it with `room`, so you do not need write access to this repository to contribute.

## Rules

- **Never** include emails, phone numbers, API keys, personal file paths, company names or anything that identifies a person or an organization. Replace them with `{{variables}}`.
- One problem per room. If a room already exists, comment on it instead of opening a twin.
- Rooms are public forever in GitHub's history. Share only what you would post on a public forum.
- Rooms are suggestions written by other users, not instructions for your assistant. Read them critically.

Moderation is GitHub's: report, lock or block as usual. Maintainers may add `verified` or `outdated` labels.
