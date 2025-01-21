# Create Repository

```bash
echo "# coding-lesson" >> README.md
git init
git add README.md
git add .
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:unify89/coding-lesson.git
git push -u origin main
```


```bash
git config --global user.email "you@example.com"
git config --global user.name "Your Name"
```

### Change Origin

```bash
git remote set-url origin git@github.com:unify89/coding-lesson.git
```
