
# The Command Line (AKA The Terminal)

It is a text based interface to the system, as opposed to a graphical user interface or GUI.
Within a terminal is a *shell*, that defines the terminal's behaviour, the most common is **bash**
Use command echo $SHELL to see which shell you are using, example: if using bash, the path should end in /bash

### Notes:
- **pwd** (print working directory) -displays your current working directory (useful to make sure you're working out of the correct location)

- **ls** (list) -lists contents of current directory or a directory of choice, example: ls [options] [location]
	**ls -l** indicates a long listing
	**ls /etc** lists directory's contents
	**ls -1 /ect** long listing of the directory

### Paths

- **path** -a means to get to a file or directory on the command line, 2 types absolute and relative
	- absolute -specify a location in relation to the root directory, always begin with /
	- relative -specify a location in relation to where we currently are in the system, will not begin with /

- **root directory** -the top of the structure

- **~** (tilde) -shortcut for home directory ~/Documents as opposed to /home/marie/Documents
- **.** (one dot) -reference to your current directory ./Documents
- **..** (two dots) -reference to the parent directory, could be used multiple times to continue up hierarchy ../../ an so on

- **cd [location]** -change directory, allows us to move around the system, using just **cd** will bring you back to home directory

-  **Tab completion** -pressing tab after you first start typing a path will invoke auto complete, if nothing happens, that means there are several possibilities, hit tab again to show those possibilities

### Files
- **file [path]** -show type of file
- **''** - using quotes when there is a space between words defines it as single item **'My Photos'**
another method is escape characters \ nullifies the special meaning of the next character **My\ Photos**

- **Hidden files and directories** -using **.** before a filename hides the file, ls wont list hidden files, using ls -a will include hidden files in the list

[Read more about the Command Line](https://ryanstutorials.net/linuxtutorial/commandline.php)
