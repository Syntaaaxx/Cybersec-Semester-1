![[class02-1.pdf]]

### **1. The Shell & Command Line Interface**

- **Definition:** The shell is a command-line interpreter (CLI) that connects the user to the kernel and executes commands based on user inputs.
    
- **Structure & Help:** Commands follow the structure `command <options> <arguments>`. Use `man <command>` or `--help` to view details.
    
- **Input/Output Redirection:**
    
    - Redirect stdout to create or overwrite a file using `>`, append using `>>`, or discard using `/dev/null`.
        
    - Pipe stdout from one command to another using `|`.
        

### **2. Linux File Management & Navigation**

- **Filesystem:** Linux treats everything as a file (including hardware and network connections) and is case-sensitive. Hidden files begin with a dot (`.`).
    
- **Navigation:** The root directory is `/`, and the tilde (`~`) represents the user's home directory. Paths can be absolute (starting from `/`) or relative (using `./` or `../`).
    
- **Inodes:** File properties are stored in index nodes (inodes), where each file has a unique inode number on a partition.
    
- **Links:** Hard links share the same inode and data, while soft (symbolic) links point to the source file path with a different inode.
    

### **3. File Permissions & Ownership**

- **Permissions:** Defined by Read (`r = 4`), Write (`w = 2`), and Execute (`x = 1`) for the **Owner**, **Group**, and **Public**.
    
- **Commands:** Permissions and ownership are modified using `chmod`, `chown`, and `chgrp`.
    

### **4. Text Editors (vi/vim & nano)**

- **vi/vim:** Operates in three main modes: _Command mode_ (for keystroke navigation/actions), _Insert mode_ (for typing text, exited via ESC), and _Ex mode_ (for colon commands like `:wq` to save and quit).
    
- **nano:** A user-friendly terminal editor controlled via shortcut keys displayed at the bottom of the interface (e.g., `Ctrl+O` to write/save, `Ctrl+X` to exit).
    

### **5. Searching and Archiving**

- **Searching:** Use `locate` (relies on a database updated via `updatedb`) or `find` (allows advanced filtering by name, type, and expressions).
    
- **Archiving:** The `tar` command is commonly used to bundle and extract files (e.g., `tar -cvf` to create an archive and `tar -zxvf` to extract a gzipped archive).
