# First Pull Request - Learn by Doing

Welcome! This repositroy is designed to help you make your very first pull request (PR) in a safe, beginner-friendly enviroment.

## What You'll Learn

- How to fork a repositroy
- How to clone your fork locally
- How to create a branch
- How to make changes and commit them
- How to push changes to GitHub
- How to create a pull request

## Your Mission

This README contains intentional typos. Your task is to:

1. Find and fix the typos
2. Submit your fixes via a pull request
3. Optionaly, add yourself to the `CONTRIBUTORS.md` file

Dont worry - you cant break anything. This is a practice repo designed for learning.

## Prerequisites

- A GitHub acount
- Git installed on your computer
- Thats it! No other software is needed.

## Step-by-Step Guide

### 1. Fork This Repository

Click the "Fork" buton at the top right of this page. This creates your own copy of the repository.

### 2. Clone Your Fork

```bash
git clone https://github.com/YOUR-USERNAME/First-PR.git
cd First-PR
```

Replace `YOUR-USERNAME` with your actual GitHub usernam.

### 3. Create a New Branch

```bash
git checkout -b fix-typos
```

You can name your branch anything descriptive, such as `fix-readme-typos` or `your-name-typo-fixes`.

### 4. Make Your Changes

Open `README.md` in your favorit text editor and fix the typos you find. Look carefuly - there are typos throughout this document.

### 5. Commit Your Changes

```bash
git add README.md
git commit -m "Fix typos in README.md"
```

### 6. Push to GitHub

```bash
git push origin fix-typos
```

### 7. Create a Pull Request

1. Go to your fork on GitHub
2. Click "Compare & pull request"
3. Add a clear title, such as "Fix typos in README.md"
4. Describe what you fixxed
5. Click "Create pull request"

Congratulation! You've just made your first pull request.

## Need Help?

- New to Git? Check out GitHub's Git Handbok
- New to pull requests? Read GitHub's PR guide
- Stuck? Open an issu and we'll help you out.

## Optional: Add Yourself as a Contributor

After fixing typos, your welcome to add your information to `CONTRIBUTORS.md`:

```markdown
### Your Name
- GitHub: [@yourusername](https://github.com/yourusername)
- LinkedIn: [Your LinkedIn](https://linkedin.com/in/yourprofile) (optional)
- About: A sentance or two about yourself!
```

## About Pull Requests

GitHub pull requests are a vital tool for colaborating on code and contributing to open source projects.

In this article, we'll cover some best practises for using pull requests effectivly to streamline your workflow and ensure that changes are reviewed and tested before being merged into the main codebase.

## Best Practices

- Create descriptive pull request titles and descriptions: When you create a pull request, be sure to give it a descriptive title that summarises the changes you've made. It's also a good idea to include a detailed description of the changes in the pull request body, including any relevent context or background information. This will help other team members understand the changes you've made and why their necessary.
- Use branches to isolate changes: When making changes to a codebase, its a good idea to create a new branch for each set of changes you want to submit. This will make it easier to review and test the changes, and it will also allow you to make additonal changes to the codebase without affecting the main branch.
- Keep pull requests small and focused: It's generaly easier to review and test smaller pull requests than larger ones. Try to limit your pull requests to a single, focused change rather then a large number of unrelated changes. This will make it easier for other team members to review and test your changes.
- Use code review tools: GitHub provides a number of tools to help you review code, including inline comments, line-by-line review, and code review templates. Use these tools to provide feedback and sugestions for improvement on the code you're reviewing.
- Respond to feedback and requests for changes: If someone leaves a comment or requests changes on your pull request, be sure to respond in a timely maner. This will help ensure that the review process stays on track and that any necesary changes are made before the pull request is merged.
- Test your changes: Before submitting a pull request, be sure to test your changes to ensure that they work as expected. This will help ensure that the changes are ready to be merged and that they dont introduce any new bugs or isues.

By following these best practices, you can streamline your workflow and ensure that your pull requests are reviewd and tested effectively. With a litte bit of practice, you'll be able to use GitHub pull requests to collaborate on code and contribute to open source projects with confidance.

## Code of Conduct

This project adheres to the Contributor Covenant. By participating, you are expected to uphold the code. Please report unacceptible behavior to Cima9642.

Happy codeing!

Remember: Everyone started as a begginer. This is your safe space to learn and make mistakes.
