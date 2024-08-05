## Solutions: Morning 3 shell script challenge  
  
```bash  
# 1  
cd /s/work/cohortXY/abc123  
# 2  
cd content/week01/shell-intro  

# 3  
nano first_n_last.sh  

####   
for filename in "$@"
do
  echo $filename
  head -n 1 $filename
  tail -n 1 $filename
  echo "--------"
done  
####  
  

# 4  
bash first_n_last.sh exercise-data/creatures/*.dat  
  
# 5  
bash first_n_last.sh exercise-data/creatures/*.dat > creatures_first_n_last.txt  
```  
  
  
[<< Back](03-shell-script-challenge.md)  
  