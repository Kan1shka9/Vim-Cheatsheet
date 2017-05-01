# Vim-Cheatsheet

#### Insert Mode
i

#### Insert mode with new line below the cursor
O

#### Insert mode with new line above the cursor
Shift + O

#### Save file
:w

#### Quit File
:q

#### Delete a line
In Noraml Mode -> dd

#### Open 2 files in split mode
```sh
$ vim -O <file_1> <file_2>
```

#### Move Cursor when split vertically
Ctrl + W + (->) or (<-)

#### Run command
| Command       | Operation             |
| ------------- |:---------------------:|
| :!w           | Save file             |
| :!ls          | List files            |
| !:python %    | execute present file  |
