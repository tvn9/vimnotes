# VIM NOTES
Just alot of tips on vim

## Quick Start  

Start vim by typing vim from the Unix terminal
$ **vim** [Enter]

To start macvim  
$ **mvim** [Enter]  

Quit vim  
From inside vim app, switch to Normal Mode pressing ESC key, then type the colon **:**   

**:q** [Enter]  
  
To quit vim without saving changes to the file  
**:q!** [Enter]  

Create and edit a new file  
$ **vim filename.txt** [Enter]    

Edit and existing file  
$ **vim filename.txt** [Enter]  

To save the changes to the file and quit  
**:wq** [Enter]    

To save the changes to the file without quiting vim  
**:w** [Enter] 

## Moving around inside a file  

To move the cusor **up, down, left** and **right**, in **Normal Mode** type **j** | **k** | **l** | **h**  
**"j"** = down one line; **"k"** = up one line; **"l"** = move right on letter; **"h"** = move left one letter.  
 
To move up, down, left, or right multiple times, just press and **hold**-**j** the letter shown above.  

To move down by page, press **Ctrl-f** 

To move up by page, press **Ctrl-b** 

Move to start of the line, press **^** or zero **0**  

Move to the end of the line, press **$**  

Move forward or back by three words, press **3w**, **3b**    

Move up or down by 5 lines, press **5j, 5k**  

Move to specific line number, example line 10, press **10gg** 

Move to beginning of the file, press **gg** or **1g**  

Move to end of the file, press **G** or **Shift-G**  

Get information about the file, press **Ctrl-g**  



## The **set** command  

To turn ruler on, type **:set ruler**  or using toggle on/off **:set ruler!**

To turn ruller off, type **:set noruler**


