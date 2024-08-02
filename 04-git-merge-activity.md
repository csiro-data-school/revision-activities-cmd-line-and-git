## Morning 4 Git merge activity  
  
1. **C**hange **D**irectory back to your work folder on the Bowen drive (`/{letter}/work/{COHORT}/{IDENT}/`)  
  
2. And then into your recipe folder `content/week01/recipe/`  
  
3. **IMPORTANT: Switch** to your `main` or `master` branch, if not already on it.  

4. Create a new file named `thoughts.txt`, write some random thoughts to it, then add and 
  commit this new file.  

5. Make a new branch named `more-thoughts` and switch to it.  

6. Add some more thoughts to `thoughts.txt`, then again add and commit these changes.  

7. Switch back to your `main` or `master` branch.  

8. A file can be renamed, with the renaming tracked by git, by using ‘`git mv`’. Try it out now with:  
```
  git mv thoughts.txt musings.txt
  git status
  git commit -m “renamed thoughts to musings”
  git graph
  ls
```  

9. Note that you now have a file named “musings.txt”, but also another branch (`more-thoughts`) 
where you had made additions to a file still named “thoughts.txt”.  
As “thoughts.txt” no longer exists, what will happen when we merge `more-thoughts` in to `main`/`master`?  
  
Try it out!:  
`  git merge more-thoughts`  
  
  
[<< Back](03-shell-script-challenge.md)  |  [Next >>](05-git-pm-activity.md)  
  