Find Command:

	Purpose:  To find the files/directories based on name,type,size

	Syntax: find <path> <expression>    #  . indicates current directory or we can give any specific path

	Options:
•	-name  < file nme>: To search with with name
•	-i  : to make case insensitive #can use -iname to search for the name along with case insensitives
•	 -type  <character>  : to search type, below characters indicates each
a)	d : to search for directory
b)	f : to search for file
c)	l : symbolic links
d)	b : block devices
e)	c : character devices
f)	p : named pipes
•	-size <+/-number_size> : to search based on size of a file  ( here + indicates greater than and – indicates less than )
•	-mtime <+/- days> : To search the files based on modification time (+ indicates more than days and – indicates less than days)
•	-mmin <+/- minutes> : as like above to search based on modification minutes
•	-perm <permissions> : based on permissions
•	-user <username> :   To search based on user created
•	-group <groupname> : To search based on group name
•	-exec : To execute the specific commands on founded files
      {} \;   end with this symbols
     {}  to indicate the current file/directory being processing
     \:   To terminate to execute


Question:
1.	Create multiple files in different locations using a single touch command, add content to these files, and then check their sizes using the ls command in a human-readable format. Next, use the find command to perform a detailed long listing of these files, applying additional options for more information.


