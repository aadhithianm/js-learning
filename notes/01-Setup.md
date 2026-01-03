```
# Day 01: Setup and Git Basics

## 🎯 Objective
Set up the development environment and learn the fundamentals of Git so that projects can be tracked, versioned, and shared properly.

---

## 1. Tools Installed

### Visual Studio Code
Used as the main code editor.

Recommended extensions:
- Prettier (code formatting)
- GitHub Pull Requests
- Live Server

### Node.js
Allows JavaScript to run outside the browser and enables package management through npm.

Check installation:
```

node -v
npm -v

```

### Git
Version control system used to track project history and collaborate.

Check installation:
```

git --version

```

---

## 2. Project Structure

Repository name: **js-learning**

```

js-learning/
notes/
practice/
projects/
README.md

```

`README.md` explains the purpose of the repository.

---

## 3. Basic Git Workflow

### Initialize Git
```

git init

```

### Stage changes
Adds files to the “staging area.”
```

git add .

```

### Commit changes
Saves a snapshot with a message.
```

git commit -m "Initial project setup"

```

### Connect to GitHub
```

git remote add origin <repository-url>
git branch -M main
git push -u origin main

```

After the first push, future pushes use:
```

git push

```

---

## 4. Key Concepts (In My Own Words)

### What does `git add` do?
It selects files that I want to include in the next commit.

### What does `git commit` do?
It permanently records the staged changes with a message describing what changed.

### What does `git push` do?
It uploads my commits from my local machine to the GitHub repository.

### Why shouldn’t GitHub be used like Google Drive?
Because GitHub is not just storage.  
It is meant for:
- version history
- collaboration
- tracking changes
- reviewing code

Simply uploading random files defeats the purpose.

---

## ✅ Summary
- Environment is ready.
- Git is installed and working.
- Repository created and pushed to GitHub.
- Understood how to track, commit, and publish code.

Day 01 complete.
```