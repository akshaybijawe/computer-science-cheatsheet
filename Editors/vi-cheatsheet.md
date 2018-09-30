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

#### Shortcuts
* a – append text after cursor
* A – append text to end of current line
* p – Command will paste the yanked line(s) contents starting on the line after your cursor.
* P – Upper case P will paste the yanked line(s) starting on the line before our cursor
* G – Takes you to specified line
* H – Takes the cursor to the top of the page
* L – Takes the cursor to the bottom of the page
* o – inserts a new line below the line your cursor is on and inserts into insert mode for typing.
* u – undo any change, must be in command mode and only goes back one change.
* w – Move over one word at a time
* Shift + G– Takes you to the bottom of the page

Reference: https://www.cs.colostate.edu/helpdocs/vi.html 
