# windows-explorer-files-selector
Select files in windows explorer by rightclicking a text file which contains a list of files to be selected and pressing select files.
# INSTALLATION

1. Go create a folder windows-explorer-files-selector in C:\Program Files\ 
2. Copy windows-explorer-file-selector.exe from this folder to C:\Program Files\windows-explorer-file-selector so the file path is C:\Program Files\windows-explorer-file-selector\windows-explorer-file-selector.exe
3. Run install selector right click menu.reg

No more steps.

P.S. you can install this tool anywhere, just open the provided .reg file and change the location in the file to your selected place.

# UNINSTALLATION

1. Delete C:\Program Files\windows-explorer-file-selector folder with contents.
2. Press ctrl+r , type regedit and press enter (to open regedit). 
3. Locate [HKEY_CLASSES_ROOT\txtfile\shell\Select file listed in this textfile] and delete the entry.

Done.

# USAGE

Create a text file containing the files to be selected. Choose to use wheather full paths or filenames. If filenames are used and not full paths, before selecting move the text file with files list to the folder where files to be selected are located.
Right click the .txt file and press select files.
Files will be selected and you can do whatever you need to do with that list of files - all windows explorer actions are available.

# POSSIBLE USE CASES

You can create a batch file using windows dir command (or any other command which let's you get a list of files you need) to export a list of files, edit it and when select the list using this tool. This might be very useful for windows power users. I did this, because didn't find any free tool online and needed to select a large file list in windows-explorer so I can right click and create symbolic links.

