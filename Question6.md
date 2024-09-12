1.Step1: Create user p1
2.Step2: He should be part of 3 groups g1,g2,g3.
3.Step3: whenever he creates a file automatically in the group section of file grp g1 should come.?


#### First, we'll create the user p1 and add them to the three groups g1 , g2, and g3. This can be done using the following commands:

#### Create user p1
## sudo useradd p1
#### Add p1 to groups g1, g2, and g3
## sudo usermod -aG g1,g2,g3 p1


### Next, we'll configure the file system to automatically set the group ownership of new files created by p1 to g1. This can be achieved by setting the setgid bit on the directory where p1 will be creating files.

####  Set the setgid bit on the directory
## sudo chmod g+s /path/to/directory

### This will ensure that any new files created in the specified directory will have their group ownership set to g1.
