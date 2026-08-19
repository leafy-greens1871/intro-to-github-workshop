# Exercise 1: Your First Commit

## Goal

Clone the repo, make a change, and push it to GitHub.

## Steps

### 1. Clone the Repository

```bash
git clone https://github.com/INSTRUCTOR-USERNAME/intro-to-github-workshop.git
cd intro-to-github-workshop
```

### 2. Create a File

Create a file named `participants/YOUR-USERNAME.md` (use your GitHub username):

```bash
touch participants/YOUR-USERNAME.md
```

Open it in VS Code and add:

```markdown
# Hi, I'm [Your Name]!

**Fun fact:** Something interesting about you
```

Save the file.

### 3. Check What Changed

```bash
git status
```

You should see your new file listed.

### 4. Commit and Push

```bash
git add .
git commit -m "Add participant YOUR-USERNAME"
git push
```

### 5. Verify

Go to the repository on GitHub — your file should appear in the `participants/` folder.

## Stuck?

| Problem | Fix |
|---------|-----|
| `Permission denied` | Let the instructor know — they'll add you as a collaborator |
| `not a git repository` | Make sure you're inside the `intro-to-github-workshop` folder |
| `nothing to commit` | Did you save the file? |
