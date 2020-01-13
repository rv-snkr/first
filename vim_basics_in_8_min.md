# Vim Basics in 8 Minutes

### Why do we need to know about using Vim

Because the basic text editor that is present in any remote Unix/Linux server is vim

How to quit Vim in the command mode type ":q" and hit enter.

Different commands in Vim

To write to file or to save
```vim
:w 
```

To save and quit
``` vim
:wq
```

To quit without saving and without confirmation
```vim
:q!
```

To set line numbering
```vim
:set number
```

### Vim is a Modal editor means it runs in modes

* Command Mode
* Insert/Edit Mode

#### How to switch between modes?

Pressing 'i' enters Insert mode
Pressing 'esc' enters Command mode

### Few more commands

To delete a line
```vim
:dd 
```

To delete 3 lines
```vim
:3dd
```
in other words, if we put a number before the command, the command is repeated those many times

To undo the changes
```vim
u
```

To redu the changes
```vim
Ctrl + r
```

For searching a string (ravi as example)
```vim
/ravi
```
The cursor will stop at the first occurrence of ravi

pressing 'n' will move the cursor to next occurrence
pressing 'N' will move the cursor to previous occurrence

For searching and replacing a string ( search ravi replace with bhuvan)
```vim
:%s/ravi/bhuvan/gc
```
the operators 'g' will replace all
the operator 'c' asks for a confirmation
if we do not need confirmation use
```vim
:%s/ravi/bhuvan/g
```


###### Ravi Andela on 13-Jan-2020


