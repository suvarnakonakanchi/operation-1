What is Git?
- Git is like a time machine for the code.
- It tracks every change you make so you can go back if something breaks.
- You work locally on your computer with Git.

What is GitHub?
- GitHub is a website where you can store your Git projects online.
- It helps you share your code, collaborate with others, and showcase your work.
  
Starting a Git Project
- Open your terminal and go to your project folder.
- Run git init → this creates a hidden .git folder (Git starts tracking your files).
- Add files: git add . or git add filename
- Save changes: git commit -m "your message"
  
- Checking Your Work
- See what’s happening: git status
- View history: git log
- Undo mistakes: git reset, git checkout, git revert (each has a different use)
  
Git Configuration
- Set your name and email (once):
git config --global user.name "Your Name"
git config --global user.email "you@example.com"

 Branching (super useful!)
- Think of branches like alternate timelines.
- Create: git branch new-feature
- Switch: git checkout new-feature
- Merge: git merge new-feature (into main)

Merge Conflicts
- Happens when two people change the same file.
- Git will show you the conflict → you fix it manually → then commit again.

GitHub Setup
- Create a repo on GitHub.
- Link it to your local project:
git remote add origin https://github.com/yourname/repo-name.git
git push -u origin main

Pushing & Pulling
- Push = send your code to GitHub: git push
- Pull = get latest changes from GitHub: git pull

GitHub Features to Explore
- README.md → your project’s intro page.
- Issues → track bugs or ideas.
- Pull Requests → suggest changes to someone else’s code.
- Forking → copy someone’s repo to your account.















