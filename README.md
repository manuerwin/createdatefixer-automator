# createdatefixer-automator
MacOS Automator Workflow to set creation date of multiple files based on the name of the folder each file is within.

This will set the creation date of each file based on the name of the folder it is within.
The folder name needs to start with YYYYMMDD.
For example “19750202 - a great day” will set the file with a create date of 2nd Feb 1975.
It will work through all child directories.
Note: if you need to bring a file create date forward, please use SetFile.

## How to use
Download and open in Automator, then save so this is available via Finder when accessing Quick Actions for a folder/directory.

Read the confirmation and select OK to continue.

## Known limitations

All directories MUST be prefixed with the date format else will error.
