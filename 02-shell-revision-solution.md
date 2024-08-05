## Solutions: Morning 2 shell revision

```bash  
# 1  
cd /s/work/cohortXY/abc123  
# 2  
cd content/week01/shell-intro/north-pacific-gyre
# 3  
ls  
# 4  
mkdir z_samples  
# 5  
cp *Z*.txt z_samples/  
# 6  
head z_samples/*  

# 7  
sort -n z_samples/*.txt | tail -n 5  
# OR  
sort -n -r z_samples/*.txt | head -n 5  
  
# 8  
sort -n z_samples/*.txt | tail -n 5 > 5_largest_z_samples.txt  
  
# 9  
for file in *.txt  
do  
  sort -n $file | head -n 1  
done  
  
# 10  
for linenumber in 2 5 9  
do  
  head -n $linenumber NENE01971Z.txt | tail -n 1  
done  
```  
  

[<< Back](02-shell-revision.md)  
  