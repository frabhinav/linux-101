# Basic Linux Commands

Linux provides a powerful command-line interface (CLI) that allows you to interact with the operating system and perform a wide range of tasks. Learning some basic commands is essential for navigating the Linux environment. In this section, we'll introduce you to fundamental commands that every Linux user should know.

## 1. `pwd` - Print Working Directory

Use `pwd` to display the current directory (folder) you are in.

Example:
```bash
$ pwd
/home/username
```

## 2. `ls` - List Files and Directories

The `ls` command is used to list the files and directories in the current location.

Example:
```bash
$ ls
file1.txt file2.txt directory1 directory2
```

## 3. `cd` - Change Directory

With `cd`, you can change your working directory to another location.

Example:
```bash
$ cd /path/to/directory
```

## 4. `mkdir` - Make Directory

Create a new directory using `mkdir`.

Example:
```bash
$ mkdir new_directory
```

## 5. `touch` - Create Empty File

Create an empty file with `touch`.

Example:
```bash
$ touch new_file.txt
```

## 6. `cp` - Copy Files and Directories

The `cp` command is used for copying files and directories.

Example:
```bash
$ cp file1.txt /path/to/destination
```

## 7. `mv` - Move or Rename Files and Directories

Use `mv` to move or rename files and directories.

Example (move):
```bash
$ mv file1.txt /path/to/destination
```

Example (rename):
```bash
$ mv old_file.txt new_file.txt
```

## 8. `rm` - Remove Files and Directories

`rm` allows you to remove files and directories. Be cautious when using it, as it deletes without confirmation.

Example (remove a file):
```bash
$ rm file.txt
```

Example (remove a directory and its contents):
```bash
$ rm -r directory
```

## 9. `man` - Manual Pages

To access manual pages and get help on commands, use `man`.

Example:
```bash
$ man ls
```
# File Viewing and Editing

## 1. `cat` - Concatenate and display the content of files.

This command reads the file and outputs its content to the terminal. It can also be used to concatenate multiple files into one.

Example:
```bash
$ cat FILE_NAME
```

## 2. `less` - View the content of files page by page.

A terminal pager program used to view the content of a file one screen at a time. It allows for both forward and backward navigation through the file.

Example:
```bash
$ less FILE_NAME
```

## 3.`more` - view the content of files page by page.

Similar to `less`, but with more limited functionality. It allows for viewing the file content page by page, but typically only allows forward navigation.

Example:
```bash
$ more FILE_NAME
```

## 4.`nano` - Simple text editor.

A straightforward text editor in the terminal. It is user-friendly and suitable for quick edits, offering basic text editing features.

Exaple:
```bash
$ nano FILE_NAME
```
## 5. `vim` - Advanced text editor (vi improved).

A powerful and advanced text editor based on vi. It provides extensive features for programming and text editing but has a steeper learning curve.

Example:
```bash
$ vim FILE_NAME
```

## 5. `head` - Display the first part of a file.

Displays the first N lines of a file. If no number is specified, it defaults to showing the first 10 lines.

Example:
```bash
$ head -n N FILE_NAME
```


## `tail` - Display the last part of a file.

Displays the last N lines of a file. By default, it shows the last 10 lines. It can also be used to monitor file changes in real-time with the -f option.

Example:
```bash
$ tail -n N FILE_NAME
```

## `grep` - Search text using patterns.

Searches for lines matching a specified pattern in a file and outputs those lines. It supports regular expressions and various options for refined searching.

Example:
```bash
$ grep 'pattern' FILE_NAME
```



These are just a few of the essential Linux commands to get you started. Experiment with these commands, and over time, you'll become more comfortable with the Linux command-line interface. 

Remember that you can use the `man` command to access manual pages for any command to learn more about its options and usage.
```

Feel free to expand upon this content or add more commands as needed for your documentation. You can include examples, explanations, and tips to help users understand and use these basic Linux commands effectively.
