sed s/>//g | sort -u WA1.fasta
grep kangaroo WA1.fasta | sed s/[a-z]//g | sed s/(,),-//g
sed s/P//g | sort WA1.fasta >> WA1.md

The first line removes the ">" character preceding the lines of the file and the sort command sorts the file alphabetically
The second line finds the lines with the string "kangaroo" and removes the alphabetical and special characters from the lines
The third line removes the capital P preceding the numbers in the names and the sorted file is then written into my personal file 
for the first weekly assignment. 
