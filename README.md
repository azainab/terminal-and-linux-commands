####If you want to get the first line, you can use sed too:

sed -n 1p file.csv

p stands for print

### delete first line

sed -i 1d file1.csv

d stands for delete

### display last few lines

 tail -3 alphabetfile
