1. Step1 Create directory /tmp/bg as root user and create files inside it.
2. Step2 “abhi” should be the owner of the directory. He should be able to create files and delete files inside    
   the directory and also he should be able to add content to all files inside the directory.?

#### Step 1: Create directory /tmp/bg as root user and create files inside it.
As the root user, we created the directory /tmp/bg and created some files inside it using the following commands:

#### Create the directory /tmp/bg
### sudo mkdir /tmp/bg

#### Create some files inside the directory
### 1 sudo touch /tmp/bg/file1
### 2 sudo touch /tmp/bg/file2
### 3 sudo touch /tmp/bg/file3

#### Step 2: “abhi” should be the owner of the directory. He should be able to create files and delete files inside the directory and also he should be able to add content to all files inside the directory.
To achieve this, we changed the ownership of the directory /tmp/bg to abhi and set the necessary permissions using the following commands:

#### Change the ownership of the directory to abhi
### 1 sudo chown abhi:abhi /tmp/bg

#### Set the permissions to allow abhi to create, delete, and modify files inside the directory
### 1 sudo chmod 700 /tmp/bg
With these permissions, abhi should be able to create files and delete files inside the directory, as well as add content to all files inside the directory.
