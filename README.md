# Git Repository Initialization

## 1. Create a new repository locally

```bash
echo "# init" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
```

## 2. Connect to a remote repository

Make sure you have already created a repository on GitHub. Copy the repository SSH or HTTPS address. Example using SSH:

```bash
git remote add origin git@github.com:Magic-Forces/init.git
```

## 3. Push your code to GitHub

```bash
git push -u origin main
```

---

## If you already have a local repository

Just add the remote repository and push everything:

```bash
git remote add origin git@github.com:Magic-Forces/init.git
git branch -M main
git push -u origin main
```

---

## Basic Git Commands

### Stage a file

```bash
git add <filename>
```

### Commit staged changes

```bash
git commit -m "commit message"
```

### Check repository status

```bash
git status
```

### Pull changes from remote

```bash
git pull
```

### Push changes to remote

```bash
git push
```
