# VIM and MACVIM NOTES 

This vimnotes document collects as many as possible the useful tips on vim and macvim

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

To move the cusor **up, down, left** and **right**, in **Normal Mode** type 
**j** = down,  **k** = up, **l** = right, and **h** = left 

To move up, down, left, or right multiple times  
**press** and **hold-j**, or **k** or **h** or **l**  

To move down by page  
press **Ctrl-f** 

To move up by page 
press **Ctrl-b** 

Move to start of the line 
press **^** or zero **0**  

Move to the end of the line 
press **$**  

Move forward or back by three words 
press **3w**, **3b**    

Move up or down by 5 lines 
press **5j, 5k**  

Move to specific line number, example line 10 
press **10gg** 

Move to beginning of the file 
press **gg** or **1g**  

Move to end of the file 
press **G** or **Shift-G**  

Get information about the file 
press **Ctrl-g**  

## Deleting text  

To delete a letter, move the cursor to the targeted letter 
press **x**  

To delete a word, move the cursor to start of the word 
press **dw**  

To delete 3 words forward 
press **3dw** or **d3w**  

To delete 3 words backward 
press **3db** or **d3b**  

To delete from current letter to end of the line 
press **d$**  

To delete from current letter to start of the line 
press **d^**  

To delete in-text a word, the cursor can locate on any letter of the word 
press **dit**  (dit = delete in text)  

To delete the whole line 
**dd**  

To delete 3 line down 
press **d3d** or **d3j**    

To delete 3 line up 
press **d3k**  

## The **set** command allows user to customize Vim features 

To learn more about vim's options available for the **.vimrc** file, 
type **:h options** 

Vim **set** command is used to set start-up features in the **.vimrc** file for Unix, Linux, and windows normally in home directory

What is ~/.vimrc?, vim = **vim**; **rc** = run command 

Unix, Linux home: ~/.vimrc

Windows: $HOME/_vimrc  

Inside the .vimrc file, enter the **set** commands without the colon: just enter **set** **option** 

Example, to turn on line number, enter **set linenumber** or **set nu** in the **.vimrc** file   

To run **set** command while in Vim, switch to **Normal Mode** 
type **:set number**

To find information about the current settings 
type **:set enter**  

To turn ruler on, type **:set ruler** or using toggle on/off **:set ruler!**

To turn ruler off, type **:set noruler**

To find information about a setting while inside vim, type **:set number?** 

To find out if search highlight is enable, type **:set hls?"**  

Set history to 1000, type **:set history=1000** or **set history=1000** inside the .vimrc file  

Show incomplete command, use **set showcmd**  

Show a menu when using tab completion, use **set wildmenu**  

Set scrolloff lines, use **set scrolloff=5**

Set incremental search, use **set incsearch**  

Set ignorecase search, use **set ignorecase** 

Turn on smart case, use **set smartcase**  

Turn on backup option, use **set backup**  

Set the default extention for the backup file, use **set bex=BACKUP**  

Set auto indentation, use **set ai**  

Set smart indentation, use **set si**  

## Working with Buffer 

Open several files at once, 
**vim file1.txt file2.txt fileN.txt Enter**  

To see the list of buffer, 
**:buffers** or **:ls** or **:files**  

While other files are opened, to open additional file, 
**:edit filename.txt** or **:e filename**  

To work on different opened files 
**:buffers filename** or **:b filename**  

To switch to file in buffer #1 
**:b1** 

To repeat to cycle through the list of opened files
**:b tab** 

**:b Ctrl-d** will bring up a list of files, then continue to type in the first few letters + tab to finish selecting the right file.  

The quickest way to move around buffers or open files is **:ls** to list the buffers, then type 
**:b 2** to select the buffer number.  

To open the next file in the buffers
**:b next** 

To delete buffer number 8  
**:bd8** 

Type **:bd** without any number will close the correct active buffer 
**:bd**  

To close the active buffer 
**:bw** 





























