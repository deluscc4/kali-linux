# Terminator

## This is a repository made for taking notes from my study.<br>

1. ``sudo su`` (root)
2. ``apt install terminator`` 
3. ``terminator`` (opening)

``CTRL + SHIFT + O`` => new tab <br>
``CTRL + SHIFT + E`` => new right tab <br>
``CTRL + SHIFT + W`` => closing tab <br>

# Linux commands

### Information

``uname -a`` => System information <br>
``uname -r`` => Kernel information <br>
``shutdown`` | ``shutdown now`` | ``shutdown -h <mins>`` => Turning the machine off <br>
``reboot`` => Restarting machine <br>
``id`` => Shows your current username (useful for reverse shell) <br>
``sudo su`` => Temporary root mode <br>
``exit`` => Exiting root mode <br>
``clear`` => Clearing the terminal <br>
``df -h`` => Memory usage information <br>

### Archives and directories

Directories are in blue (**d**rwxr-xr-x), files (-rw-r--r--) are in white. <br>
``[~]`` = Home <br>
``ls`` => Listing directories in a horizontal line<br>
``ls -l`` => Listing directories in a list <br>
``ls -a`` => Listing hidden archives in the folder <br>
``ls -al`` => Listing hidden archives in a list <br>
``pwd`` => Printing working directory <br>
``ls /home/kali/Desktop`` => Listing a specific directory (note that Kali is case sensitive) <br>
``touch /home/kali/Desktop/archive_name_to_create.txt`` => Creating a new archive <br>
``cd <directory_name>`` => Changing to specified directory <br>
``cd ..`` => Going back a directory or ``cd ../..`` two directories <br>
``mkdir <directory_name>`` => Making a new directory or ``mkdir <directory_name>/<directory_name>`` to create without being inside <br>
``mv <archive> <directory>`` => Moving file to another folder <br>
``mv <archive_name> <new_archive_name>`` => Renaming an archive <br>
``cp <archive> <directory>`` => Duplicate file to another directory or ``cp <archive> <directory>/<new_name>`` with a new file name <br>
``rm <archive>`` => Deleting a file <br>
``rm -rf <directory> => Deleting a directory <br>

### Query commands

``find /path/path_2 *.txt`` => Searching for every .txt file in the given path <br>
``locate *.txt`` => Searching for every .txt file in the entire system <br>
``locate *.bkp | grep <search>`` => Searching for every .bkp file in the entire system with given <search> in any part of the file name <br>
 
 ### Compacting files
 
 ``zip <new_file_name>.zip <archive_name>`` => Compressing file <br>
 ``unzip <compacted_file_name>.zip`` => Decompressing file <br>
 ``tar -cvzf <new_file_name>.tar <archive_name>`` => Compressing file <br>
 ``tar -xvzf <compacted_file_name>.tar`` => Decompressing file <br>
 
 ### Users and groups
 
 ``groupadd <group_name>`` => Creating a new group <br>
 ``useradd <user_name> => Creating a new user <br>
 ``gpasswd -a <user_name> <group_name>`` => Adding a user to a group <br>
 
 ### Reading archives
 ``cd /usr/share/wordlists`` => Accessing wordlists
 ``CTRL + Z`` => Exiting file reading
 
 ``cat <archive_name>`` => Reading file <br>
 ``more <archive_name>`` => Reading a huge file (usually a wordlist) from the top to the bottom <br>
 ``less <archive_name>`` => Reading a huge file (usually a wordlist) from the bottom to the top <br>
 ``head -2 <archive_name>`` => Reading only the first TWO (2) lines of the archive <br>
 ``tail -2 <archive_name>`` => Reading only the last TWO (2) lines of the archive <br>
  ``head -f <archive_name>`` => Reading an archive (usually logs) in real time <br>
 
 ### Network
 
 ``hostname`` => Machine's name <br>
 ``ifconfg`` => Showing IPs and network cards <br>
 ``ip addr show`` => Showing IPs and interfaces <br>
 
 ``wget <picture_URL>`` => Downloading a picture from the internet
 
 ### Text editor
 
 ``nano <archive_name>`` => Using Nano text editor <br>
 ``CTRL + O`` => Saving
 ``CTRL + X`` => Exiting
 
 ``vim <archive_name>`` => Using Vim text editor <br>
 ``insert`` to start typing <br>
 ``esc`` + ``:wq`` to save and quit <br>
 ``esc`` + ``:wq!`` to save and forcibly quit also from another opened editor <br>
  ``esc`` + ``:q`` to only quit <br>
 









  
