# Git

This is git tutorial and you have to follow the steps to learn merge.

# Step 1: Create a new branch

```bash

git checkout -b new-branch
```

# Step 2: Make changes in the new branch

Change in the same this line and add anything at the end of this line.

# Step 3: Add and commit the changes

```bash
git add .
git commit -m "Made changes in new-branch"
```

# Step 4: Switch back to the main branch

```bash
git checkout main
```

Write something in some line that you edit it in step 2. Then, commit what you changed.

```bash
git add .
git commit -m "Made changes in main branch"
```

# Step 5: Merge the new branch into the main branch

```bash
git merge new-branch
```

# Step 6: Resolve any merge conflicts

Then you have to solve the conflicts. _Much easier than solving Middle East conflicts_
After you solve the conflicts, you have to save the file then contenaure the merge process.

```bash
git merge --continue
```

That is it.
