Here you go — all of it in **one clean Markdown block**, ready to paste into a `README.md` or doc:

````markdown
# 🧪 Git Branching Cheat Sheet (Bash)

## 🔧 Create a New Branch
```bash
git checkout -b your-branch-name
````

Creates and switches to the new branch.

---

## 🔄 Switch to an Existing Branch

```bash
git checkout your-branch-name
```

---

## 🔍 List All Local Branches

```bash
git branch
```

---

## 🧹 Delete a Branch

```bash
git branch -d your-branch-name
```

* `-d` = safe delete (only if merged)
* `-D` = force delete (even if not merged)

---

## 🚀 Push a New Branch to Remote

```bash
git push -u origin your-branch-name
```

Links your local branch to the remote tracking branch.

---

## 🔁 Merge a Branch into Main

```bash
git checkout main
git merge your-branch-name
```

---

## 💥 Abort a Merge (if needed)

```bash
git merge --abort
```

---

```

Paste that into your Markdown doc — it's all set. Let me know if you want one for GitHub PR workflow next.
```
