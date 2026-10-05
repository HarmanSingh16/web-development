# Contributing

## Where does it go?
- Related to a specific class: that class's folder under `classes/`.
- Spans several classes: `cheatsheets/`.
- Interesting but fits no class: `interesting/`.

## Entry format (one line per resource)
```
- [Title](url): why it's worth your time · level: core | extra | advanced · added by @username
```
A link with no "why" will be asked to add one in review.

## Rules
1. **Don't copy the teacher's files into this repo.** Link to them. The teacher's repo is the source of truth.
2. **Links to the teacher's folders must be URL-encoded.** Their folder names contain spaces and
   parentheses, which break Markdown links. Copy the link from the class README instead of retyping it.
3. Only commit files you wrote yourself, or that are clearly licensed for reuse. Otherwise link.
4. One pull request = one class or one theme. Fill in the PR template.
5. Found an error in the teacher's notes? Open an issue on their repo, not a fix here.

## Adding a new class
Copy an existing `classes/class-XX-*/` folder, rename it, update the two lines at the top,
and add a row to the table in the root `README.md`.
