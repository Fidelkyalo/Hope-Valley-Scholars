---
description: Commit and push all changes to GitHub after making edits
---

// turbo-all

After making any edits to files in this project, always run the following steps:

1. Stage all changes
```
git -C "c:\Users\user\OneDrive\Desktop\HOPE VALLEY SCHOLARS" add -A
```

2. Commit with a descriptive message summarizing what was changed
```
git -C "c:\Users\user\OneDrive\Desktop\HOPE VALLEY SCHOLARS" commit -m "Update: [brief description of changes]"
```

3. Push to GitHub
```
git -C "c:\Users\user\OneDrive\Desktop\HOPE VALLEY SCHOLARS" push origin main
```

Note: If the working tree is already clean (no changes to commit), skip these steps — the VS Code Git Autocommit extension may have already pushed the changes automatically.
