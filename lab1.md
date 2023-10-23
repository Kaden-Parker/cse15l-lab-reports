# Cd Command

![Image](cd.png)

1) When I first typed cd into the console nothing showed up since it requires a directory to change to. However, once I changed the directory to something else, cd with a blank argument would return the default working directory, in this case, it was /home. The current working directory before any argument was inputted was home. If I was in a different directory and cd'ed without an argument would return to home. There were no errors with this command. 

2) When I typed cd lecture1 it changed the current working directory into lecture1. The current working directory was changed into lecture1 once the command ran. There was no error since this is the intended use of the command.

3) When I tried to change the directory into a relative or absolute path it gave me an error that the arguments were not directories. This error seems to be shared with any argument that is not a directory. The working directory was home when I ran the command. 

# Ls Command

![Image](ls.png)

1) When I typed ls into the console with no argument it showed the folders within /home which was lecture1. The working directory at this time was home since there was no cd before this command. There were no errors with this command. 

2) When I typed ls with the path to the directory it showed all files and folders contained in lecture1, for Edstem it showed folders with  blue text to separate the two. The working directory was also still home since there was no cd command. There were no errors with this command.

3) When I typed ls with a path to a file, it repeated the argument given in the console. The working directory was still home since there were no changes to the directory. There was no error message given.

# Cat Command

![Image](cat.png)

1) When I typed in cat with no argument it waited for an argument to concatenate with so the prompt was left empty until I force-stopped the console. The working directory was home since there was no cd command. There was no error with this command since it was just waiting for a follow-up for the cat command.

2) When I typed in cat with a directory it gave the error message that lecture1 is a directory. Since concatenate prints the contents of files of given paths it makes sense that it gives an error message with a directory as an argument. The working directory at the time was home. 

3) When I typed in cat with a path to a file it displayed the file's contents in the console. The working directory was home. There was no error message since this is the intended use of the cat command. 
