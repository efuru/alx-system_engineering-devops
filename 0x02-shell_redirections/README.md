I/O Redirection: Input and Output Redirection.

By using some special notations we can redirect the output of many commands to files,

devices, and even to the input of other commands.

Standard Output:

most command lines displays their results,

by seding it to the standard outpu.

By default standard utput directs it's contents to the display.

e.g: ls > file_list.txt  in this code, ls command is excuted and the results are outputed in the file_txt file


Standard Input: 
many command accepts input from Standard input

by default it accepts contents from the keyboard but it can also be redirected.

To redirect standard input from a file instead of the keyboard, the "<" character is used.

e.g: sort < file_list.txt in this code

sort is used to process the contents of file_list.txt

and the results are outputed via the display since the standard output was not redirected

to redirect the above code: file_list.txt 
