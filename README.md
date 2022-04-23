# createdatefixer-automator
MacOS Automator Workflow to set creation date of multiple files based on the name of the folder each file is within.

This will set the creation date of each file based on the name of the folder it is within, provided the folder name starts with a date in the format YYYYMMDD.
For example “19750202 - a great day” will set the file with a create date of 2nd Feb 1975.
You can select multiple folders and/or a top-level folder containing many folders.
Will ignore folders without date prefix.
Will ignore files within top-level folder.

## How to use
Download and uncompress the zip, then save the .workflow to your ~/Library/Services directory.
This 'should' make it available as a right-click Quick Action for you.

Either select a top-level folder and/or multi-select folders with files you wish to fix the create date.
Right-click > Quick Actions > CreateDateFixer.
Read the confirmation and select OK to continue.

## Known limitations

KNOWN LIMITATION: Will not bring a file create date forward, for example from 1975 to 1999, please use SetFile.