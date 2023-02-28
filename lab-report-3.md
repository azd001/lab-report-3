I chose to research the find command. 4 interesting command-line options that I found were -delete, -cmin, -atime, -user.

The first command was -delete. This command allows you to delete files that are returned by find.

If we were to run find "test.txt" -delete, the file "test.txt" will be deleted from the directory. 

![image](before_delete.png)

![Image](after_delete.png)

One example where this is useful, we can use find to locate a directories, and files and use -delete to delete all of those files in one go.

Another example is when we pair -name and -delete together. If we know the specific name of a file, we can use -name to locate and follow up with -delete to remove only the file.
