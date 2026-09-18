# Contributing to Sketchstra

Thanks for your interest in Sketchstra!

The project is developed openly under the **Mahistra** organization. Anyone is welcome to contribute — students, beginners, developers, designers, researchers, testers, and documentation writers. You do not need to understand the entire project before making your first contribution.

This guide explains how to pick up an issue, make changes, and submit a pull request (PR).

---

## Code of Conduct

Be respectful and constructive. This project is a place to learn and build together. Harassment of any kind will not be tolerated.

---

## What the project is

Sketchstra is a web-based visual canvas. The plans and goals live in [`plan.md`](plan.md) — please read it before starting. The most important principle:

> Don't make drawing complicated. Make the experience better.

## Tech stack (V1)

- **Frontend:** React + TypeScript
- **Rendering:** HTML Canvas or SVG (decision tracked in [#4](https://github.com/Mahistra/Sketchstra/issues/4))
- **Testing:** Vitest (once #26 is merged)
- **Backend:** none for V1

---

## Getting started

1. Make sure you have **Node.js** installed (LTS recommended).
2. Fork the repository on GitHub.
3. Clone your fork and set up the project:

```bash
git clone https://github.com/<your-username>/Sketchstra.git
cd Sketchstra
npm install
npm run dev
```

Then open the URL shown in your terminal (usually http://localhost:5173).

> Coming soon: there is an open issue ([#1](https://github.com/Mahistra/Sketchstra/issues/1)) to set up this exact project scaffold. Until it is merged, the setup above may evolve. Ask in the issue comments if anything is unclear.

---

## Finding something to work on

Browse the [issues list](https://github.com/Mahistra/Sketchstra/issues) and pick one.

### Difficulty labels

| Label | Meaning |
| --- | --- |
| `good first issue` | Small scope, no deep project knowledge needed; great place to start |
| `difficulty:easy` | Beginner-friendly, focused change |
| `difficulty:medium` | Requires understanding of the relevant area |
| `difficulty:hard` | Requires deeper, system-level understanding |

### Area labels

`area:foundation`, `area:canvas`, `area:tools`, `area:ui`, `area:files`, `area:testing`, `area:docs`, `area:ci`.

### Rules for picking an issue

- One issue per PR unless the issues explicitly say otherwise.
- If an issue is already assigned to someone, pick a different one.
- If you want to work on an issue, **comment on it** (e.g. "I'll take this one") so others know it is claimed.
- If an issue doesn't have enough detail to start, comment with your questions before opening a PR.

---

## Making changes

1. Create a branch from `main` with a short, descriptive name:

```bash
git checkout -b feat/add-fill-settings
```

Useful prefixes: `feat/`, `fix/`, `docs/`, `refactor/`, `test/`, `chore/`.

2. Make focused, reviewable changes. Keep the scope to what the issue asks for.
3. Do not add unrelated changes, even tiny ones — reviewers will ask you to split them out.
4. Try to add or update tests for behavior you change (core drawing/editing logic, especially).
5. Run the checks before committing:

```bash
npm run lint
npm run test
npm run build
```

If these commands aren't set up yet, run them anyway and note what happens in the PR description.

6. Commit with a short, clear message describing what your change does, not how you did it:

```bash
git add .
git commit -m "feat: add fill settings to the stroke and fill panel"
```

Keep the change in one commit unless it genuinely represents separate steps.

---

## Submitting a pull request

1. Push your branch to your fork:

```bash
git push -u origin feat/add-fill-settings
```

2. Open a pull request against the `main` branch of `Mahistra/Sketchstra`.
3. In the PR description, mention which issue it closes:

```md
Closes #30
```

Use the full phrase `Closes #N` so GitHub links and auto-closes the issue when merged.

4. Fill in the PR description with:
   - What was changed and why
   - How it was tested
   - Any screenshots or recordings if the change is visual

5. Link the issue number somewhere visible (title or description).

### After submitting

- Watch for CI results. If a check fails, fix it and push again.
- If a reviewer leaves comments, address them, push updates, and reply to each comment.
- Keep the conversation going until the PR is approved.

---

## Review expectations

- Reviews should be kind and specific: explain the reason behind each request.
- You may receive suggestions in addition to required changes. Required changes are blocking; suggestions are optional.
- If a request looks unclear, ask instead of guessing.

---

## Code style & quality principles

From `plan.md`:

- **Keep the code understandable.** Prefer clarity over cleverness.
- **Prefer small, reviewable changes.**
- **Test important behavior.** Core drawing and editing logic should have tests.
- **Performance matters.** Keep the canvas responsive as drawings grow.

---

## Getting help

- Comment on the issue you're working on.
- Open a [discussion](https://github.com/Mahistra/Sketchstra/discussions) if one is enabled.
- Don't be afraid to ask beginner questions — everyone starts somewhere.

---

## Thank you

Every contribution, no matter how small, moves Sketchstra toward a better drawing experience. Welcome aboard!