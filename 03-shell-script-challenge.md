## Morning 3 shell script challenge  
  
1. **C**hange **D**irectory back to your work folder on the Bowen drive (`/{letter}/work/{COHORT}/{IDENT}/`)  

2. And then into `content/week01/shell-intro/`  

3. Write a script named `first_n_last.sh` that, when given a list of files as argument(s), 
  will, for each file (hint: **for** and **$@**), **do** the following:  
    - Print (**echo**) the file name
    - Print the first line of the file
    - Print the last line of the file
    - Print “--------”
  (Note, these are each separate steps, on different lines, within your loop)  
  
4. Try running your script on `exercise-data/creatures/*.dat`  
  You should see:  
```
    exercise-data/creatures/basilisk.dat
    COMMON NAME: basilisk
    CGCGCCCACC
    -------
    exercise-data/creatures/minotaur.dat
    COMMON NAME: minotaur
    GCCTTCACGG
    -------
    exercise-data/creatures/unicorn.dat
    COMMON NAME: unicorn
    CGCGCCCACC
    -------
```  
  
5. Repeat 4., but direct the output to a file named `creatures_first_n_last.txt`  
  (Do not modify the script to achieve this, do it through the command line when running the script)  
  
  
[<< Back](02-shell-revision.md)  |  [Next >>](04-git-merge-activity.md)  
  