# Find Command:

## Purpose:  
To find the files/directories based on name,type,size

## Syntax: 
**`find <path> <expression>`**  ##indicates current directory or we can give any specific path

## Options:
* **-name**  < file nme>: To search with with name
* -i  : to make case insensitive #can use -iname to search for the name along with case insensitives
* **-type**  <character>  : to search type, below characters indicates each
  1. d : to search for directory
  2. f : to search for file
  3. l : symbolic links
  4. b : block devices
  5. c : character devices
  6. p : named pipes
* **-size** <+/-number_size> : to search based on size of a file  ( here + indicates greater than and – indicates less than )
* **-mtime** <+/- days> : To search the files based on modification time (+ indicates more than days and – indicates less than days)
* **-mmin** <+/- minutes> : as like above to search based on modification minutes
* **-perm** <permissions> : based on permissions
* **-user** <username> :   To search based on user created
* **-group** <groupname> : To search based on group name
* **-exec** : To execute the specific commands on founded files
     1. {} \;   end with this symbols
     2. {}  to indicate the current file/directory being processing
     3. \:   To terminate to execute


### Question:
1.	Create multiple files in different locations using a single touch command, add content to these files, and then check their sizes using the ls command in a human-readable format. Next, use the find command to perform a detailed long listing of these files, applying additional options for more information.


