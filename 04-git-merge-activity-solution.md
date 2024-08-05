## Solutions: Morning 4 Git merge activity  
  
```bash  
# 1  
cd /s/work/cohortXY/abc123  
# 2  
cd content/week01/recipe  
  
# 3  
git switch main  
  
# 4  
nano thoughts.txt  
git add thoughts.txt  
git commit -m "Added thoughts file"  
  
# 5  
git branch new-thoughts  
git switch new-thoughts  
  
# 6  
nano thoughts.txt  
git add thoughts.txt  
git commit -m "Added some new thoughts in"  

# Review where we are
git log --oneline  
  
# 7  
git switch main  

# What does 'thoughts.txt' look like on main branch?  
cat thoughts.txt  
  
# 8  
git mv thoughts.txt musings.txt  
git status  
git commit -m "renamed thoughts to musings"  
git graph  
ls  
  
# 9  
git merge more-thoughts  
  
# How did that go?  
ls  
cat musings.txt  
```  
  
  
[<< Back](04-git-merge-activity.md)  
  