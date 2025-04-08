# Developer Guide

## Connecting to the ServisWork Repository (GitHub)

### 1. Clone the project (SSH)
```bash
git clone git@github.com:ServisWorks/serviswork-mvc.git
```

### 2. Navigate to the project folder
```bash
cd serviswork-mvc
```

### 3. Check SSH connection to GitHub
```bash
ssh -T git@github.com
```

### 4. Check current branches
```bash
git branch
```

### 5. Create a new branch (for a task)
```bash
git checkout -b feature/task_name
```

### 6. Work with code and commit changes
```bash
git add .
git commit -m "Added: task description"
```

### 7. Push changes to GitHub
```bash
git push -u origin feature/task_name
```

---

## GitHub CLI Commands (if used)

### Check authentication
```bash
gh auth status
```

### Log in to GitHub
```bash
gh auth login
```

---

## Local project address:
```
http://localhost:5192/
```

## Project path on Mac:
```
/Users/gennadii/Desktop/serviswork_Core/ServisWork
```

---

If you have questions about working with Git, contact Gennadii.
