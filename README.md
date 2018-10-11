# scvcs : concurrent versioning and cats for strings
Strings sharing and versionning

ssc

ssc 'all_git_commands'

ssc add string_value [file]
* Add a new string to be tracked. If [file] try to link it to it

ssc link string_id file
* Link a string identifier to a file

ssc unlink string_id [file]
* Unlink a string identifier from a file

ssc out [string_id] [file]
* Extract the new version of the string identifier from a file 

ssc in [string_id] [file]
* Put a new version of the string in a file
