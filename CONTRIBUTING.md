# Contributing Guide

Welcome to this Data Science Learning Repository! This guide outlines the best practices for making commits and organizing contributions within this repository.

---

## 📜 Commit Message Style Guide

### ✅ Commit Structure:

```

<type>: <short, imperative summary>

<body (optional)>
```

---

### 🔥 Commit Types:

| Type       | Purpose                                                        |
| ---------- | -------------------------------------------------------------- |
| `docs`     | Documentation only (README, notes, diagrams)                   |
| `feat`     | New files, projects, notebooks, or features                    |
| `fix`      | Fixes (typos, broken links, minor corrections)                 |
| `chore`    | Repo maintenance (file renames, folder reorganizing)           |
| `refactor` | Improve code/notebooks without changing output                 |
| `style`    | Visual/style changes (formatting, whitespace, no logic change) |
| `data`     | Add or update datasets                                         |
| `wip`      | Work-in-progress snapshot (optional, if useful)                |

---

### ✍️ Commit Title (Subject Line) Rules:

* Use **present tense**:
  ✅ `add`, `fix`, `update` (❌ not `added` or `fixed`)
* No period at the end.
* Keep it **≤ 50 characters** (soft limit).
* Be specific and concise.
* Start with a **type prefix**, followed by a colon and space.

---

### 📝 Commit Body (Optional):

* Wrap lines at \~72 characters.
* Explain **why** the change was made or provide extra context.
* Leave blank if the title is sufficient.

---

## 💡 Examples:

```
docs: add initial README with repository purpose and goals

Includes sections for goals, folder structure, tools, about me,
and reasons for keeping the repository public.
```

```
feat: add pandas practice notebook for data wrangling
```

```
fix: correct broken link to LinkedIn in README
```

```
chore: rename Theory folder to Concepts for clarity
```

```
wip: draft notebook for exploratory data analysis project
```

---

## 🏗️ Commit Frequency Suggestions:

| Context                    | When to Commit                                         |
| -------------------------- | ------------------------------------------------------ |
| **Notes**                  | After finishing a concept/module/lesson                |
| **Notebooks (practice)**   | After completing a section (e.g., EDA, modeling)       |
| **Projects**               | After meaningful milestones (e.g., data cleaning done) |
| **README or docs**         | After completing logical sections or revisions         |
| **Repo structure updates** | Immediately when structure changes                     |

---

## 🚀 Additional Practices:

* Keep commits meaningful and atomic.
* Avoid generic commit titles like "update" or "stuff."
* Commit often, but group logically related changes together.

---

Thank you for following this guide to keep the repository clean, readable, and useful!
