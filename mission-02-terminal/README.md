## Mission 2: Terminal and File Management

### Task 2.1: Terminal Commands

| Command | Description |
|---|---|
| `pwd` | Displays the current working directory. |
| `ls` | Lists files and directories. |
| `ls -l` | Displays detailed information about files and directories. |
| `ls -a` | Displays hidden files and directories. |
| `ls -lah` | Displays all files with detailed information and human-readable sizes. |
| `cd ..` | Moves to the parent directory. |
| `mkdir` | Creates a new directory. |
| `touch` | Creates an empty file. |
| `cp` | Copies a file from one location to another. |
| `mv` | Moves or renames a file. |
| `cat` | Displays the contents of a file. |
| `echo` | Prints text or writes text into a file. |
| `head` | Displays the first few lines of output. |

### Task 2.2: File Management Practice

| Activity | Command Used | Result |
|---|---|---|
| Create a practice directory | `mkdir terminal-practice` | Directory created successfully. |
| Create a text file | `touch notes.txt` | Empty file created. |
| Add first line | `echo "First line" > notes.txt` | First line added to the file. |
| Append second line | `echo "Second line" >> notes.txt` | Second line added without replacing the first line. |
| Display file contents | `cat notes.txt` | Both lines displayed. |
| Create a backup | `cp notes.txt backup.txt` | A copy of the file created. |
| Rename the original file | `mv notes.txt final_notes.txt` | File renamed successfully. |

### Task 2.3: Important Concepts

| Concept | Explanation |
|---|---|
| Absolute Path | The complete path starting from the root directory. |
| Relative Path | A path specified relative to the current working directory. |
| Overwrite (`>`) | Replaces the existing content of a file. |
| Append (`>>`) | Adds new content without deleting existing content. |
| Copy (`cp`) | Creates a duplicate while keeping the original file. |
| Move (`mv`) | Moves a file to another location or renames it. |
| Pipe (`\|`) | Passes the output of one command as input to another command. |
| Package Manager | A tool used to install, update and manage software packages.