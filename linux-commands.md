# Linux Commands

In order to navigate through Linux, a user must be familiar with a few basic commands to get around.

## cd

- The CD command allows users to *Change Directory*. This allows users to navigate through file paths for visibility and management of contents. 
`cd fakepath/fake-sub-directory`

## mkdir

- Mkdir is used to *create a directory*, or a new folder to host content 
This operation is completed by navigating to your target location, and using the following command
`mkdir newfolder` where "newfolder" is the name of the new directory. 

## cp

- Copy is used to *copy* a file or directory to a new location.
This command may be formatted one of two ways:
`cp file1.txt target/folder` (to move a single file to a new location)
_or_ 
`cp * target/folder` (to copy all files in a directory to the target location)

## pwd (Print Working Directory)

- Pwd allows users to *print working directory*, or output the entire directory that you are currently working within. 
`/bin/pwd`

## mv

- The mv command holds the ability to Move OR Rename files as needed. Users can move files from one directory to another, or rename a file to a new title in an existing directory.
Move Example: `mv desired_path/file target_path/sub folder`
Rename Example: `mv file1.txt file1_new.txt`

## rm 

- Remove allows users to delete files or folders.
`rm filename.txt`

## History

- The *History* command hows a log of all commands performed in the Unix shell. This operation is completed by typing `history` into the shell and pressing Enter.

## Home Directory and ~

- The *Home Directory* is the filepath the storage location that hosts a user’s personal files, folders, and executable programs. The tilde (~) can be used to reference the home directory.
`cd ~` can take a user back to their home directory.

## File Paths in Linux

- *File paths* represent a file or folder’s location within a Linux interface. Users may navigate through different file paths by using the `cd` command to change directories, both upstream and downstream.

## Using the tab key to complete file paths

- Users may utilize the “tab” key to autocomplete a file path.
For example - if you have a file named Brandon.jpg, you can navigate to the directory where the file is stored and type “br” before pressing the Tab key. Autocomplete will fill in the remainder of “Brandon.jpg” for you.

## Using up and down arrow for history

- Users may utilize the up and down arrow keys on their keyboard to cycle through previously used commands. This allows ease of access for repetitive commands, as the user can pre-fill the command line with a previous command from the shell’s history.
