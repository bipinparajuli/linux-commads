# Basic Linux Command
Command | Description
---- | ----
ls | List all files and directories on the present working directory.
ls -R | Also list files of sub-directories.
ls -a | List hidden files as well
ls -al | List files and directories along with detail information like permissions,size,owner etc.
cd or cd~ | Navigate to home directory
cd .. | Move one level up
cd path | Change to particular directory
cd / | Move to root directory
cat > filename | create new file
cat filename | display the content of filename
cat file1 file2>file3 | join (file1 and file2) and stores the output on the newfile i.e file3
mv file "new file path" | Moves the file to the new location
mv existing_file_name new_file_name | rename to new file name
sudo | Allow regular user to run programs with the security previlages of root or superuser
rm filename | delete a file 
man | gives help information on a command
history | gives a list of all command run on current terminal session
clear | clear the terminal
mkdir dirname | make a directory 
rmdir | removes a directory
apt-get | command to install and update packages

# Process Command

Command | Description
---- | ----
bg | Send process to background
fg | Run stopped process on the foreground
top | detail on all active process
ps | gives the status of process running for a user
ps PID | gives the status of particular process
pidof | gives the process id of process
kill PID | kill the process
nice | Starts a process with given priority
renice | Change the priority of already running process
df | gives the free hard disk on a system
free | gives the free RAM of a system
