# Github + Huggingface

### Class Description

```
Github + Huggingface
อ.ปรานปวีณ (พี่เลย์)
09/04/2567 13:00 - 16:00
```

### Materials
- [Slide](https://drive.google.com/drive/folders/1EM4p7UCuVJcF8lwP-mZo0XnPS7wkuoqU)

## My Scratch Paper

### >> Git and Github
- Git Configuration
```
git config --global user.name yourname
git config --global user.mail youremail@gmail.com
```

### [ Basic Flow ]
- Git Initialization
```
# Create New Local Repository
git init
```

- Stage and Unstage
```
# Add File to Staging
git add .

# Unstage File and Folder
git rm --cached <file>
git rm -r --cached <folder>
```

- Git Commit (Save Checkpoint)
```
git commit -am "your comment here"
```

- Push to Remote Repository (Github)
```
git push
```

- Monitoring
```
# check file staging
git status

# check commit history
git log
```

- Move to Previous Commit
```
# git checkout <commit_id>
```

### [ Branch ]
```
# create new branch
git branch feat1

# check current branch
git branch

# move to new branch
git checkout feat1

# create and move to new branch
git checkout -b feat2

# push to remote branch
git push -u origin <branch>
```

### [ Merge ]
```
# typical merge (อาจเป็น fast-forward)
git merge <branch>

# no fast-forward merge
git merge --no-ff <brach_to_merge>
```

### >> Github Action
- Act - Run workflow on local
### >> Huggingface
### >> MLOps
- Decay Monitoring (update model เมื่อ score ตกถึงค่า threshold)
- CI -> CT (Continuous Training) -> CD
