# Exercise 2: Working with Branches

## Goal

Create a branch and make changes on it without affecting `main`.

## What's a Branch?

A branch is a separate workspace. You can try things out without touching the main version.

## Steps

### 1. Create a New Branch

```bash
git checkout -b add-YOUR-USERNAME
```

Replace `YOUR-USERNAME` with your GitHub username.

### 2. Create a File

Create a file named `contributions/YOUR-USERNAME.md` and add:

```markdown
# Hi, I'm [Your Name]!

**One thing I learned today:** (fill this in later!)
```

Save it.

### 3. Commit Your Change

```bash
git add .
git commit -m "Add contribution from YOUR-USERNAME"
```

### 4. Push Your Branch

```bash
git push -u origin add-YOUR-USERNAME
```

Go to your fork on GitHub — you should see your new branch listed.

## Key Takeaway

Branches let you work on something new without affecting `main`. Your changes stay on your branch until you're ready to merge.
