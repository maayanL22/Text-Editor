# Text-Editor

vim styled text editor in c, implements all main features in a text editor including a search feature, syntax highlighting, etc...
you can of course open a file with it, and the syntax highlighting will be done automatically by the program, personally i added syntax highlighting support to c, cpp, header and python files but you are more than welcome to add anything you desire, it can be done simply by adding the desired file extensions, keywords and chars to highlight in the filetypes segmant at the top of the code.
scrolling through files is done with the keys, and in order to quit just press ctrl-q, if you make changes to the file but do not save them (using ctrl-s) a warning will be raised when trying to quit and you will have to press ctrl-q 3 times (you can change that easily as well if you would like).

you will not be able to run it on windows machines unless you will use some kind of linux environment (personally i used virtualbox with ubuntu).
for convenience i added a makefile.
