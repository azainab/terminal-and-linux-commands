####If you want to get the first line, you can use sed too:

sed -n 1p file.csv

p stands for print

### delete first line

sed -i 1d file1.csv

d stands for delete

### display last few lines

 tail -3 alphabetfile
 
 ### create tunnelling
 
 ssh -L 4040:localhost:4040 user@xx.tamu.edu

 ssh -L 4040:localhost:4040 <nodename>
 
 Access the website at localhost:4040
 
 ### In a single line tunneling of spark master node
 
 ssh -L 8080:compute.node.name:8080 username@your.server.name
 
## copying a file to a server from desktop
scp local_file user@remote_host:remote_file
