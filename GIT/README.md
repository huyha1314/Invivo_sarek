# TUTORIAL_GIT Daily work

## Phase 1 - setup 
### First update github
```bash 
git checkout main 
git pull origin main 
```

### Create branch for adding new-feature
```bash
git checkout -b new-feature # -b mean adding
```

## Phase 2 - work 

```bash 
git status
```

```bash
git add . # for everyfile
git add ./README.md 
```

```bash
git commit -m "Daily procedure"
git push origin new-feature
```

```bash
git status
git checkout main 
git merge new-feature
git push origin main
```

## Phase 3 - clean up 

```bash
git branch -d new-feature
```
