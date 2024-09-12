What is grep commond use for in linux?

### In Linux, the grep command is a powerful tool used for searching and filtering text patterns in files or output streams. The name "grep" comes from the phrase "global regular expression print"

# Common uses of grep:

#### Searching for a specific string:
## grep "hello" file.txt
This command searches for the string "hello" in the file file.txt and prints the lines that contain the string.

#### Searching for a pattern in multiple files:
## grep "hello" *.txt
This command searches for the string "hello" in all files with the .txt extension in the current directory.

#### Searching for a pattern in the output of a command:
## ls -l | grep "file.txt"
This command searches for the string "file.txt" in the output of the ls -l command.

#### Counting the number of matches:
## grep -c "hello" file.txt
This command counts the number of lines that contain the string "hello" in the file file.txt.

#### Searching for a pattern recursively:
## grep -r "hello" .
