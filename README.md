# -Linux-Commands-Basics-
# Basic Linux/Ubuntu Commands 🚀

Here are some essential commands I’ve learned while exploring Linux/Ubuntu:

- **Change directory**: `cd`
- **Go back one folder**: `cd ..`
- **Create a file**: `touch`
- **Go back two folders**: `cd ../..`
- **Current working directory**: `pwd`
- **See content of a file**: `cat`
- **Edit text with**: `vi`
- **Move files or folders**: `mv`

Feel free to connect with me and share more tips! Let’s grow together! 💻

---

### How to use:
1. Open your terminal.
2. Try these commands and level up your skills!

#Linux #Ubuntu #CommandLine #OpenSource

## 📂 Directory and File Operations

- **List Directory Contents**: `ls`
  - Display contents of the current directory.

- **Detailed Directory Listing**: `ls -l`
  - Show detailed information of files and directories.
  
  Example:
drwxr-xr-x 2 manishkumar manishkumar 4096 Sep 6 16:27 manke

markdown
Copy code
- `d`: Directory indicator.
- `rwx`: Permissions for owner.
- `r-x`: Permissions for group.
- `r-x`: Permissions for others.
- `2`: Number of hard links.
- `manishkumar`: Owner.
- `manishkumar`: Group.
- `4096`: Size in bytes.
- `Sep 6 16:27`: Last modified date and time.
- `manke`: Directory name.

- **List Contents of a Specific Directory**: `ls -l <directory>`
- Show details of a specific directory without changing to it.

- **List All Files and Subdirectories**: `ls -R`
- Display all files and directories recursively.

- **Find Recently Modified Files**: `ls -lt`
- Sort files by modification time, showing the most recent first.

- **View Hidden Files**: `ls -a`
- List all files, including hidden ones (those starting with `.`).

- **Print Directory Size**: `du -sh <directory>`
- Display the size of a directory in a human-readable format.

- **Find Files by Extension**: `ls *.txt`
- List files with a specific extension, e.g., `.txt`.

- **List Files Starting with a Specific Name**: `ls <name>*`
- Show files starting with a given prefix.

- **List Parent Directory Folders**: `ls ../`
- Show folders in the parent directory from the current location.

## 📝 File Content Management

- **View File Content**: `cat <filename>`
- Display the contents of a file.

- **Add New Content to a File**: `echo "New content" > <filename>`
- Create or overwrite a file with new content.

- **Append Content to a File**: `echo "Additional content" >> <filename>`
- Add content to the end of an existing file.

## 📁 Directory Management

- **Create and Move to Directory**: `mkdir <directory> && cd <directory>`
- Create a new directory and change into it.

- **Create Directories Recursively**: `mkdir -p <path/to/directory>`
- Create a directory and any necessary parent directories.

- **Remove a Non-Empty Directory**: `rm -r <directory>`
- Delete a directory and its contents.

## 🔒 File Permissions

- **Remove Permissions**: `chmod u-x <filename>`
- Remove execution permission from the user.

| Permission | Description                 |
|-------------|-----------------------------|
| `r`         | Read                        |
| `w`         | Write                       |
| `x`         | Execute                     |
| `-`         | No Permission               |

Permissions are divided into:
- **User**: Owner of the file.
- **Group**: Users who are members of the file's group.
- **Others**: All other users.

## 🛠️ Advanced Commands

- **Grep**: Search for patterns within files.
- **Awk**: A versatile programming language for pattern scanning and processing.
- **Sed**: Stream editor for filtering and transforming text.
- **Download Node.js**: Follow instructions on [Node.js official website](https://nodejs.org/en/download/).

---

Feel free to reach out if you have any questions or need further assistance!
