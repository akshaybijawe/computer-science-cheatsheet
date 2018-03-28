# vi editor cheatsheet

* It is the default editor that comes in the UNIX based operating systems. vi stands for **vi**sual editor.

* There are 2 modes of operation:  
   1. **Command** mode: It causes an action to be taken on the file which is being edited.  
   2. **Insert** mode: Any text typed is inserted in the file.  

### List of commands:  

#### Starting vi
**vi** filename: edit filename starting at line number  
**vi** -r filename: recover filename that was being edited when system crashed. 

#### Exiting vi
To exit the vi editor, press *esc* key and type *colon* (:), and then press enter typing the below commands.  
* **:x** (Return): quit vi, writing out modified file to file named in original invocation  
* **:wq** (Return): quit vi, writing out modified file to file named in original invocation  
* **:q** (Return): quit (or exit) vi  
* **:q!** (Return): quit vi even though latest changes have not been saved for this vi call  










Reference: https://www.cs.colostate.edu/helpdocs/vi.html 