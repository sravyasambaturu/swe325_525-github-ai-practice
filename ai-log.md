# AI-Use Log

## AI interaction 1

- **Date:** 2026-09-29
- **Assistant:** Claude (Anthropic)
- **Purpose:** Understand core GitHub concepts before starting the assignment
- **Prompt or summary:** Asked Claude to explain the difference between a repository, branch, commit, pull request, and issue.
- **Useful suggestion:** Claude explained that a repository is the project's full storage including all files and history; a branch is a movable pointer to a line of commits that allows isolated development; a commit is a focused, saved snapshot of one change with an explanatory message; a pull request is a proposal to merge one branch's changes into another, with room for review and discussion; and an issue is a tracked unit of planned work or discussion, often used to define goals or acceptance criteria before work begins.
- **Decision:** Accepted
- **Reason:** I added the issue link since it makes the repository easier to navigate and lets a reviewer trace the work back to its original goal without searching manually. I kept the full workflow list in the README instead of trimming it, because a first-time visitor to the repo shouldn't need to open workflow-notes.md just to understand the basic process - the short list adds minimal length but real value for someone skimming the README alone.

**Related GitHub URL:** [Commit 8478b19](https://github.com/sravyasambaturu/swe325_525-github-ai-practice/commit/8478b1948236b25dcfee242efad9c42e5be828e6)

---

## AI interaction 2

- **Date:** 2026-09-29
- **Assistant:** Claude (Anthropic)
- **Purpose:** Get feedback on README.md clarity before finalizing it
- **Prompt or summary:** Asked Claude to review my README.md and suggest revisions for clarity.
- **Useful suggestion:** Claude suggested adding a direct link to the GitHub issue so readers can find where the work is tracked, simplifying the author line, and trimming the workflow list since it duplicates content already covered in `workflow-notes.md`.
- **Decision:** Revised
- **Reason:** I added the issue link since it makes the repository easier to navigate. I kept the full workflow list in the README instead of trimming it, because I wanted the README to be understandable on its own without needing to open a second file.

**Related GitHub URL:** [Commit 532cb2a](https://github.com/sravyasambaturu/swe325_525-github-ai-practice/commit/532cb2adf57595d880cf0863f0dcc0aa382f9483)

---

## AI interaction 3

- **Date:** 2026-09-29
- **Assistant:** Claude (Anthropic)
- **Purpose:** Get a checklist to structure my pull-request description
- **Prompt or summary:** Asked Claude to suggest a checklist for a complete pull-request description.
- **Useful suggestion:** Claude provided an eight-item checklist covering a clear title, a summary paragraph, a linked issue, a list of included commits, an acceptance-criteria checklist, verification notes, an AI-assistance disclosure, and known limitations or follow-up work.
- **Decision:** Accepted
- **Reason:** The checklist matched almost exactly what the assignment requires in the pull-request description, so I used it directly as the structure for my pull request.

**Related GitHub URL:** [Pull request #2](https://github.com/sravyasambaturu/swe325_525-github-ai-practice/pull/2)

---

## Reflection

**1. Which GitHub action or object was most useful to you, and why?**
- The issue was the most useful starting point, since writing out the acceptance criteria and task checklist up front made it clear exactly what "done" looked like before I wrote a single commit.

**2. Which AI suggestion did you accept, and what made it useful?**
- I accepted the pull-request checklist suggestion because it was specific and directly matched what the assignment already required in a PR description, so it saved me from guessing at the right structure.

**3. Which AI suggestion did you revise or reject, and why?**
- I revised the README suggestion, I added the issue link as recommended, but chose to keep the full workflow list rather than trimming it, since I preferred the README to stand on its own.

**4. What did you verify yourself instead of trusting the AI?**
- I verified that the actual GitHub branch, commit, and issue links were correct by checking them directly on GitHub rather than assuming placeholder text was accurate.

**5. What would you change in your GitHub workflow next time?**
- I would write the issue's acceptance criteria in more detail before starting the branch, so the commits could map even more directly to specific, checkable outcomes from the start.