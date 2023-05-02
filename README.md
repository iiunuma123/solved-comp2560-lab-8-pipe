Download Link: https://assignmentchef.com/product/solved-comp2560-lab-8-pipe
<br>
Write a C program with the parent process and a child process communicating with a pipe. The child process will execute the shell command provided by the user via command line arguments. The result of executing this shell command is passed to the parent process using a pipe. The parent process will write the result into a file called result.txt and acknowledge the user on the screen with the shell command and the total number of bytes in the result.

For simplicity, the shell command contains only the command name, no argument.

You can only use <em>read</em>, <em>write</em>, <em>close</em> for pipe operation.




Sample run:





