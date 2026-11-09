 Contribution Guidelines

1. Issue Tracking & Acceptance Criteria

Before starting work on a feature, ensure there is an open issue for it.

Track Progress with Checkboxes: Our issues come with an "Acceptance Criteria" section that includes checkboxes. As you work through the issue, tick off these boxes to track your progress and keep the team updated. Ensure all criteria are met and checked off before marking your Pull Request as ready for review.

2. Branch Naming Conventions

Every new feature or bug fix must be done on a separate, dedicated branch. Do not commit directly to the main or master branch.

When creating a new branch, you must follow this exact naming rule, making sure to include the \ (backslash) and # characters:

Format: feat\\#&lt;issue-number&gt;\\&lt;short-description&gt;

Example: feat\\#42\\add-user-login

Example: fix\\#42\button-alignment

3. Committing Changes

We prefer a detailed commit history over massive, single-commit PRs.

Make Multiple Commits: Try to make multiple, atomic commits for a feature or issue. Break your work down into logical chunks (e.g., "implement wWinMain", "register global hotkeys", "add floating mode") rather than pushing everything in one giant commit.

Clear Commit Messages: Write descriptive commit messages. We highly recommend using Conventional Commits (e.g., feat: register global hotkeys, fix: resolve crash on exit).

4. Pull Requests (PRs)

When your feature is ready, open a Pull Request against the main branch.

Link the Issue: You must mention the issue you are solving in the PR description. Use GitHub keywords like Resolves #42, Fixes #42, or Closes #42 so the issue automatically closes when the PR is merged.

Provide Context: Briefly describe what changes you made and why. If there are visual changes, consider adding a screenshot.
