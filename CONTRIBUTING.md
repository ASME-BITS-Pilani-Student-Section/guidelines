# Contributing Guidelines

This repository defines standards for maintaining clean, readable, and scalable codebases across the club.
Follow these guidelines strictly when contributing.

---

## 1. Branching Strategy

* **Do not commit directly to `main`**
* Always create a new branch for your work

**Branch naming format:**

```
type/short-description
```

**Examples:**

* `feat/add-oled-driver`
* `fix/timer-overflow-bug`
* `docs/update-contributing-guide`

---

## 2. Making Changes

* Keep changes **small and focused**
* One branch = one logical change
* Avoid mixing unrelated changes in a single PR

---

## 3. Commit Messages

Write **clear, descriptive commit messages**.

**Format:**

```
type: short summary
```

**Types:**

* `feat` → new feature
* `fix` → bug fix
* `docs` → documentation changes
* `refactor` → code restructuring (no behavior change)
* `test` → adding/modifying tests

**Examples:**

* `feat: add ultrasonic sensor driver`
* `fix: correct PWM frequency calculation`
* `docs: update setup instructions`

**Rules:**

* Use present tense ("add", not "added")
* Keep it concise (≤ 72 characters for summary)
* Explain *why* in the body if needed

---

## 4. Pull Requests

* Open a PR **only after your work is ready**
* PRs should be **reviewable in under 10 minutes**

**PR Title:**
Same format as commit messages

**PR Description must include:**

* What changes were made
* Why they were made
* Any dependencies or notes for reviewers

---

## 5. Code Readability

* Use meaningful variable and function names
* Add comments where logic is non-obvious
* Maintain consistent formatting

---

## 6. Before Submitting

* Ensure your code builds/runs correctly
* Remove debug prints and unnecessary files
* Rebase or sync with `main` if needed

---

## 7. Review Process

* Be open to feedback
* Address review comments before merging
* Do not merge your own PR unless explicitly allowed

---

## 8. Golden Rule

> If someone unfamiliar with your project cannot understand your changes in 5 minutes, your contribution is not ready.

---

Following these guidelines ensures that every repository in the club remains clean, professional, and easy to navigate.
