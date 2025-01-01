# **CMD Commands Reference**

## 🖥️ **Basic Commands**
- `help`  
  *Displays a list of available commands.*
- `cls`  
  *Clears the screen.*
- `exit`  
  *Exits the command prompt.*

---

## 📂 **File and Directory Commands**
- `dir`  
  *Lists files and subdirectories in a directory.*
- `cd [path]`  
  *Changes the directory.*
- `mkdir [folder]`  
  *Creates a new folder.*
- `rmdir [folder]`  
  *Deletes a folder (empty only).*
- `del [file]`  
  *Deletes one or more files.*
- `copy [source] [destination]`  
  *Copies files to another location.*
- `move [source] [destination]`  
  *Moves files to another location.*
- `ren [oldname] [newname]`  
  *Renames a file or directory.*
- `tree`  
  *Displays the directory structure.*
- `attrib`  
  *Views or modifies file attributes.*

---

## 🖥️ **System Information**
- `systeminfo`  
  *Displays detailed system information.*
- `hostname`  
  *Displays the computer's hostname.*
- `ver`  
  *Displays the Windows version.*
- `set`  
  *Displays, sets, or removes environment variables.*
- `tasklist`  
  *Lists all running processes.*
- `taskkill /IM [process_name] /F`  
  *Ends a task or process.*

---

## 🌐 **Networking Commands**
- `ipconfig`  
  *Displays IP configuration.*
- `ping [address]`  
  *Sends packets to test connectivity.*
- `tracert [address]`  
  *Traces route to an address.*
- `netstat`  
  *Displays active connections and ports.*
- `nslookup`  
  *Resolves domain names.*
- `arp`  
  *Displays or modifies ARP cache.*
- `netsh`  
  *Configures network settings.*
- `telnet`  
  *Starts a Telnet session.*

---

## 👥 **User and Permissions**
- `net user [username]`  
  *Views user information.*
- `net user [username] [password] /add`  
  *Adds a new user.*
- `net localgroup [groupname] [username] /add`  
  *Adds a user to a group.*
- `net share`  
  *Displays shared resources.*
- `whoami`  
  *Displays the current username.*

---

## 💽 **Disk and Partition Commands**
- `diskpart`  
  *Launches the disk partitioning utility.*
- `chkdsk [drive]:`  
  *Checks the disk for errors.*
- `format [drive]:`  
  *Formats a disk.*
- `vol`  
  *Displays the volume label and serial number.*
- `wmic`  
  *Provides advanced disk and system management.*

---

## 🔄 **System Operations**
- `shutdown /s /t [time]`  
  *Shuts down the computer.*
- `shutdown /r /t [time]`  
  *Restarts the computer.*
- `sfc /scannow`  
  *Scans and repairs corrupted system files.*
- `powercfg`  
  *Configures power settings.*
- `diskcleanup`  
  *Opens the disk cleanup tool.*

---

## ⚙️ **Advanced Commands**
- `regedit`  
  *Opens the registry editor.*
- `gpupdate`  
  *Refreshes group policies.*
- `taskmgr`  
  *Opens Task Manager.*
- `sc`  
  *Communicates with Windows service control.*
- `schtasks`  
  *Manages scheduled tasks.*

---

## 🔒 **Security and Troubleshooting**
- `cipher`  
  *Encrypts or decrypts files.*
- `fc [file1] [file2]`  
  *Compares two files.*
- `eventvwr`  
  *Opens the Event Viewer.*
- `msinfo32`  
  *Displays system information.*
- `sfc /scannow`  
  *Checks and repairs system files.*

---

## 💻 **Programming and Development**
- `echo [text]`  
  *Displays text in the command prompt.*
- `type [file]`  
  *Displays file content.*
- `more [file]`  
  *Displays file content one screen at a time.*
- `find [string] [file]`  
  *Searches for a string in a file.*

---

## 🌟 **Miscellaneous**
- `time`  
  *Displays or sets the system time.*
- `date`  
  *Displays or sets the system date.*
- `color`  
  *Changes the text color.*
- `title [title]`  
  *Sets the title for the CMD window.*
- `pause`  
  *Pauses a batch file execution.*
