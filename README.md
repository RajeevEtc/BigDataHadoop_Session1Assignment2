# BigDataHadoop_Session1Assignment2
1. __pwd__: Used to display the current working directory

2. __vi__: It used to open VI Editor. The vi editor (short for visual editor) is a screen editor which is available on almost all Unix systems. 

Example: To create/open a file, following command can be used:
              $ vi filename

3.__touch__: The touch command updates the access and modification times of each FILE to the current system time.

Example: $touch testfile.txt

    If file.txt exists, touch updates its access and modification times to the current time. If file.txt doesn't exist, it is created as a new, empty file.
    
4.__mkdir__: Used to create a new directory.

Example: $mkdir music

    Creates a new directory called mydir whose parent is the current directory.
    
5.__rm__: It removes files or directories.

Example: $rm -r mydirectory

         It will remove the directory mydirectory, and any files and directories it contains. If a file or directory that rm tries to delete is write-protected, you will be prompted to make sure that you really want to delete it.
         $rm 
         
 6. __ls__: Displays the list of files and directories available under current directory.
 
  Example: a) $ls : list out the name of the files and directories
           b) $ls -l : list out the files and directories along with details like permissions, size, creation date etc.
  
 7. __echo__: Displays the line of text in the output console.
 
  Example: $echo Hello, World
   Output: Hello, World
 
 8. __cat__: It can be used to 
                      a)display the contents of a file in command line, 
                      b)copy the contents of a file to a new file
                      c)concatenate the contents of the two different file and store in new file or displays on the command
                      line
   Example: $cat file.txt : Displays the contents of file.txt on command line screen
 
 9. __who__: The who command prints information about all users who are currently logged in.
  Example: $who
  Output: rajeevranjan console  Jul 11 21:06 
          rajeevranjan ttys000  Jul 11 23:58
 
 10. __cd__: The cd command, which stands for "change directory", changes the shell's current working directory.
  Example: $cd myDirectory : changes the current working directory to myDirectory.
 
 11. __date__: The date command is used to print out, or change the value of, the system's time and date information.
  Example: $date
  Output: Wed Jul 12 00:58:04 IST 2017
 
 12. __cal__: Displays calender of current month from command line in standard calender format.
 Example: $cal
 Output:
 July 2017
Su Mo Tu We Th Fr Sa
                   1
 2  3  4  5  6  7  8
 9 10 11 12 13 14 15
16 17 18 19 20 21 22
23 24 25 26 27 28 29
30 31
 
 13. __mv__:The mv command is used to move or rename files.
 Example:$mv file.txt myDir/
 Output: Moves file.txt to myDir available under current working directory
 
 14. __cp__:The cp command is used to make copies of files and directories.
Example: $cp t1.txt t2.txt
Output: The contents of t1.txt will be copied to t2.txt. If t2.txt does not exists then it will created newly otherwise its contents will be over-written.
 
 15. __which__: Locate the executable file path associated with a given command.
 Example: $which sh
 Output: /bin/sh




