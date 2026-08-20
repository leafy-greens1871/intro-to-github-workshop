# Exercise 1: Your First Commit

## Goal

Fork the repository, clone your fork, create a branch, make a change, and push it to GitHub.

## Steps

### 1. Fork the Repository

1. Open the instructor’s repository on GitHub:
   `https://github.com/INSTRUCTOR-USERNAME/intro-to-github-workshop`
2. Select **Fork** in the top-right corner.
3. Choose your GitHub account as the owner.
4. Select **Create fork**.

You now have your own copy of the repository.

### 2. Clone Your Fork

Replace `YOUR-USERNAME` with your GitHub username:

~~~bash
git clone https://github.com/YOUR-USERNAME/intro-to-github-workshop.git
cd intro-to-github-workshop
~~~

### 3. Create and Check Out a Branch

Create a new branch for your work:

~~~bash
git checkout -b add-YOUR-USERNAME
~~~

Confirm which branch you are using:

~~~bash
git branch
~~~

The `*` should appear beside `add-YOUR-USERNAME`.

### 4. Create a File

Create a file named `participants/YOUR-USERNAME.md`:

~~~bash
touch participants/YOUR-USERNAME.md
~~~

Open it in VS Code and add:

~~~markdown
# Hi, I'm [Your Name]!

**Fun fact:** Something interesting about you
~~~

Save the file.

### 5. Check What Changed

~~~bash
git status
~~~

You should see your new file listed.

### 6. Commit and Push

~~~bash
git add .
git commit -m "Add participant YOUR-USERNAME"
git push -u origin add-YOUR-USERNAME
~~~

### 7. Verify

Open your fork on GitHub and select the `add-YOUR-USERNAME` branch. Your file should appear in the `participants/` folder.

GitHub may also display a **Compare & pull request** button, which you can use to propose adding your change to the instructor’s original repository.

## Stuck?

| Problem | Fix |
|---|---|
| `Repository not found` | Confirm that you forked the repository and used your GitHub username in the clone URL |
| `not a git repository` | Make sure you are inside the `intro-to-github-workshop` folder |
| `nothing to commit` | Make sure you created and saved the file |
| Branch already exists | Run `git checkout add-YOUR-USERNAME` instead |
| Push asks for a password | Sign in using GitHub CLI, a personal access token, or an SSH key |