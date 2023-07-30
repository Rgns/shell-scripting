# shell-scripting
shell-scripting basic commands and presentation

```
// check the path of bash in the system


\Rg $which bash 
/bin/bash



// create new bash Script file named : hello_world.sh 

\Rg $touch hello_world.sh



// Add commands to new bash Script file named : hello_world.sh

\Rg $vi hello_world.sh

//Insert
i

#! /bin/bash
echo "Hello Ritu!"

// write and quit
:wq



// Check bash Script listed in the directory

\Rg $ls
hello_world.sh



// Check bash Script privilage

\Rg $ls -l
total 8
-rw-r--r--  1 Ritu.Gupta  staff  32 Jul 30 15:18 hello_world.sh



// Add execution privilage to bash Script

\Rg $chmod u+x hello_world.sh 



// re-Check bash Script privilage 

\Rg $ls -l                   
total 8
-rwxr--r--  1 Ritu.Gupta  staff  32 Jul 30 15:18 hello_world.sh



// Run bash Script

\Rg $./hello_world.sh 
Hello Ritu!


\Rg $bash hello_world.sh 
Hello Ritu!
\Rg $
