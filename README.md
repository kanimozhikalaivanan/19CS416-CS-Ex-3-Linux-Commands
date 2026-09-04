# 19CS416-CS-Ex-3-Linux-Commands

**Linux** is an open-source operating system, and its kernel is the heart of the OS, facilitating communication between hardware and software. One of the key advantages of Linux is its customizability; developers can modify the Linux kernel to create their own tailored operating systems.

## Linux Commands

Linux commands are executed in the terminal, which is case-sensitive. This guide covers some basic and advanced commands used in Linux.

### 1. `ls` Command

The `ls` command is used to display a list of contents in a directory.

**Syntax:** 
```bash
ls
```

**Output:**
<img width="855" height="68" alt="image" src="https://github.com/user-attachments/assets/9a7ad846-ec6b-4257-8826-1de4e9312018" />

### 2. `pwd` Command

The `pwd` command displays the location of the current working directory.

**Syntax:**
```bash
pwd
```

**Output:**
<img width="250" height="67" alt="image" src="https://github.com/user-attachments/assets/5dc5e0f5-a805-4092-ae6a-06d68083f6a4" />

### 3. `mkdir` Command

The `mkdir` command is used to create a new directory.

**Syntax:**
```bash
mkdir <directory_name>
```

**Output:**
<img width="930" height="116" alt="image" src="https://github.com/user-attachments/assets/8650d907-56d5-4668-92ee-35f250a99b20" />

### 4. `rmdir` Command

The `rmdir` command is used to delete a directory.

**Syntax:**
```bash
rmdir <directory_name>
```

**Output:**
<img width="888" height="127" alt="image" src="https://github.com/user-attachments/assets/d577f4d4-0544-4493-b04e-a7c6b685258e" />

### 5. `cd` Command

The `cd` command is used to change the current directory.

**Syntax:**
```bash
cd <directory_name>
```

**Output:**
<img width="354" height="158" alt="image" src="https://github.com/user-attachments/assets/849d9f9d-f875-41fe-ac1d-ac6bf2dce61a" />

### 6. `cat` Command

The `cat` command is used to create, display, and concatenate files.

**Syntax:**
```bash
cat [OPTION]... [FILE]...
```

**Output:**
<img width="350" height="183" alt="image" src="https://github.com/user-attachments/assets/b8e4d538-21a4-4e27-9575-72caa113982f" />

### 7. `cp` Command

The `cp` command is used to copy files or directories.

**Syntax:**
```bash
cp <source_file> <destination_file>
```

**Output:**
<img width="334" height="133" alt="image" src="https://github.com/user-attachments/assets/1f07bcdf-4b10-4896-bd08-0728d77be955" />

### 8. `gedit` Command

`gedit` is a general-purpose text editor used to create and edit text files.

**Syntax:**
```bash
gedit <file_name>
```

**Output:**
<img width="501" height="40" alt="image" src="https://github.com/user-attachments/assets/d0f77f2b-d314-4764-b81c-a449b7b99a36" />

### 9. `su` Command

The `su` command provides administrative access to another user.

**Syntax:**
```bash
su <username>
```

**Output:**
<img width="296" height="88" alt="image" src="https://github.com/user-attachments/assets/87aba151-a75a-4675-8517-850d08192167" />

### 10. `mv` Command

The `mv` command is used to move a file or directory from one location to another.

**Syntax:**
```bash
mv <file_name> <directory_path>
```

**Output:**
<img width="363" height="265" alt="image" src="https://github.com/user-attachments/assets/f2ecc65a-e39c-4965-b877-6dca4d171c77" />

### 11. `rename` Command

The `rename` command is used to rename files.

**Syntax:**
```bash
rename 's/old-name/new-name/' <files>
```

**Output:**
<img width="462" height="171" alt="image" src="https://github.com/user-attachments/assets/af1bab27-6e12-4350-bcd8-1de5ce08c143" />

### 12. `head` Command

The `head` command displays the first 10 lines of a file.

**Syntax:**
```bash
head <file_name>
```

**Output:**
<img width="394" height="528" alt="image" src="https://github.com/user-attachments/assets/450c9181-634a-48a5-8821-35049cf9c18b" />

### 13. `tail` Command

The `tail` command displays the last 10 lines of a file.

**Syntax:**
```bash
tail <file_name>
```

**Output:**
<img width="299" height="238" alt="image" src="https://github.com/user-attachments/assets/df5fbfcd-9e0d-46f4-809c-a720175a59d3" />

### 14. `id` Command

The `id` command displays the user ID (UID) and group ID (GID).

**Syntax:**
```bash
id
```

**Output:**
<img width="931" height="48" alt="image" src="https://github.com/user-attachments/assets/c3898b7f-93b0-4325-98b9-c6ebd7d03db1" />

### 15. `grep` Command

The `grep` command is used to search for a pattern within files.

**Syntax:**
```bash
command | grep <search_word>
```

**Output:**
<img width="349" height="74" alt="image" src="https://github.com/user-attachments/assets/c5e50fba-95ba-4cba-90ad-18b529cba2a6" />

### 16. `tr` Command

The `tr` command is used to translate or delete characters.

**Syntax:**
```bash
command | tr <old> <new>
```

**Output:**
<img width="465" height="299" alt="image" src="https://github.com/user-attachments/assets/f799811a-b846-4e66-8ad7-ebe8222b14bc" />

### 17. `chmod` Command

The `chmod` command is used to change the access mode (permissions) of a file.

**Syntax:**
```bash
chmod <options> <permissions> <file_name>
```

**Output:**
<img width="450" height="118" alt="image" src="https://github.com/user-attachments/assets/3cc17f9f-e316-4f2b-bcaa-ecc6ab9e658c" />

### 18. `tar` Command

The `tar` command is used to create or extract archive files.

**Syntax:**
```bash
tar [options] [archive-file] [files_to_archive]
```

**Output:**
<img width="369" height="159" alt="image" src="https://github.com/user-attachments/assets/53e8e6f7-a726-4453-b226-38aae4929b19" />

### 19. `chown` Command

The `chown` command is used to change the ownership of a file.

**Syntax:**
```bash
chown <owner_name> <file_name>
```

**Output:**
<img width="472" height="132" alt="image" src="https://github.com/user-attachments/assets/2e203281-8992-48d7-8d2b-6a064020dd61" />

### 20. `make` Command

The `make` command is used to build and maintain groups of programs.

**Syntax:**
```bash
make [-f makefile] [options] [targets]
```

**Output:**
<img width="233" height="67" alt="image" src="https://github.com/user-attachments/assets/a22be45c-c5aa-486f-b8aa-09f331b1dcba" />

### 21. `ifconfig` Command

The `ifconfig` command is used to configure network interfaces.

**Syntax:**
```bash
ifconfig [options] [interface]
```

**Output:**
<img width="861" height="104" alt="image" src="https://github.com/user-attachments/assets/914c6747-a771-445f-9de4-a08ad8783835" />

### 22. `chmod 777` Command

The `chmod 777` command gives read, write, and execute permissions to the owner, group, and others.

**Syntax:**
```bash
chmod 777 <file_name>
chmod -R 777 /path/to/file/or/folder
```

**Output:**
<img width="493" height="118" alt="image" src="https://github.com/user-attachments/assets/29e3f374-906e-4f91-b867-e499f22d4805" />

### 23. `host` Command

The `host` command is used to display the IP address for a given domain name.

**Syntax:**
```bash
host <domain_name> or <ip_address>
```

**Output:**
<img width="605" height="101" alt="image" src="https://github.com/user-attachments/assets/405e5b13-0f3c-47de-bcdd-e3bfb4a58c93" />

### 24. `gzip` Command

The `gzip` command is used to compress files, replacing the original file with a compressed one with a `.gz` extension.

**Syntax:**
```bash
gzip <file1> <file2> <file3>...
```

**Output:**
<img width="926" height="148" alt="image" src="https://github.com/user-attachments/assets/1053b1ac-df0b-45eb-93c5-404e253670d9" />

### 25. `sort` Command

The `sort` command is used to sort the contents of a file alphabetically.

**Syntax:**
```bash
sort <file_name>
```

**Output:**
<img width="246" height="303" alt="image" src="https://github.com/user-attachments/assets/9a68d380-70f1-47cb-925b-87cf958473a1" />

### 26. `cal` Command

The `cal` command displays the current month's calendar with the current date highlighted.

**Syntax:**
```bash
cal
```

**Output:**
<img width="515" height="294" alt="image" src="https://github.com/user-attachments/assets/5a617e9d-3b21-40a2-9b6c-4d88ac0234f7" />

### 27. `clear` Command

The `clear` command clears the terminal screen.

**Syntax:**
```bash
clear
```

**Output:**
<img width="1920" height="1165" alt="image" src="https://github.com/user-attachments/assets/a3342bf8-3c66-4af1-8baa-f024247d7c41" />

### 28. `mail` Command

The `mail` command is used to send emails from the command line.

**Syntax:**
```bash
mail
```

**Output:**
<img width="930" height="298" alt="image" src="https://github.com/user-attachments/assets/d499a6df-54d1-4826-a4b0-87c76a9fdc8f" />

### 29. `df` Command

The `df` command displays the disk space usage of file systems.

**Syntax:**
```bash
df
```

**Output:**
<img width="293" height="85" alt="image" src="https://github.com/user-attachments/assets/b38759b6-c449-4209-aab6-29c48a34bfa2" />

### 30. `find` Command

The `find` command is used to search for files in a directory hierarchy.

**Syntax:**
```bash
find <directory> -name <file_name>
```

**Output:**
<img width="293" height="85" alt="image" src="https://github.com/user-attachments/assets/7ba4bdc9-1e68-4fdf-9bb5-2827c5e8dccf" />
<img width="351" height="75" alt="image" src="https://github.com/user-attachments/assets/b6f273d2-aa24-4ec5-bf82-6ca6dd8d3e40" />

## Result
Thus, the execution of various Linux commands is executed successfully using Kali Linux.
