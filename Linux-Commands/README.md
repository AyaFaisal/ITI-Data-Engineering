 # Linux Commands  
 This folder includes essential Linux commands for file management, user permissions, process control, and scripting.  
 
 ## 1.File System Navigation
 Learn how to navigate through directories and manage files.


    Command     	Description	                                   Example
    pwd	            Displays the current directory path.	        pwd
    cd	            Changes the current directory.	                cd /home/user/Documents
    ls	            Lists the contents of a directory.	            ls
    ls -l	        Lists contents with detailed information.	    ls -l
    ls -a	        Lists all files, including hidden files.	    ls -a
  # Example:
    cd /home/user/Documents
    ls -l

==============================================================================    
# 2.File and Directory Operations
These commands allow you to create, delete, and manage files and directories.

    Command	            Description	                                    Example
    touch	            Creates a new empty file.	                touch newfile.txt
    mkdir	            Creates a new directory.	                mkdir newdir
    rm	                Deletes a file.	                            rm oldfile.txt
    rm -r	            Deletes a directory and its contents.	    rm -r olddir/
    cp	                Copies files or directories.	            cp file1.txt backup/
    mv	                Moves or renames files or directories.	    mv oldfile.txt newfile.txt

## Example:
    touch example.txt
    mkdir newfolder
    cp example.txt newfolder/
    mv example.txt new_example.txt
    rm example.txt
============================================
# 3.File Permissions
Understanding file permissions and managing them is critical for security.


    Command	            Description	                                Example
    chmod	            Changes file permissions.	                chmod  script.sh
    chown	            Changes file ownership.    	                chown user:user file.txt
    ls -l	            Displays file permissi.                     ls -l
    chmod +x	        Adds execute permission to a file.	        chmod +x script.sh
     
## Example:
    chmod  myscript.sh
    chown user:user myfile.txt
    ls -l
=========================================================
# 4.Process Management
Learn how to manage running processes on Linux.


    Command	        Description                                     	Example
    ps	            Displays the currently running processes.	        ps
    top	            Real-time process monitoring.	                    top
    kill	        Terminates a process by PID.	                    kill 1234
    killall	        Terminates all processes with the given name.	    killall processname

=======================================================================================

# 5.Package Management 
Learn how to install, update, and remove software packages.

## For Debian-based systems (Ubuntu):

    Command	                  Description	                                Example
    apt update    	        Updates the list of available packages.	        sudo apt update
    apt upgrade         	Upgrades all installed packages.	            sudo apt upgrade
    apt install	            Installs a new package.	                        sudo apt install python3
    apt remove	            Removes an installed package.	                su do apt remove python3
====================================================================================================
 
 ##### "Essential Linux Commands ############
 
    Category            	            Command	                     Use	                                 Example
    File/Directory Navigation
    	                                pwd     	        Prints the current directory path	            pwd
                                        ls	                Lists directory contents	                    ls -l
                                        cd	                Changes the current directory	                cd /var/www
                                        mkdir	            Creates a new directory	                        mkdir test_folder
                                        rmdir	            Removes an empty directory	                    rmdir test_folder
    File Management             	    touch	            Creates an empty file	                        touch myfile.txt
                                        cp	                Copies files or directories	                    cp file1.txt /home/user/
                                        mv	                Moves or renames files/directories	            mv oldname.txt newname.txt
                                        rm	                Deletes files or directories	                rm -r myfolder
                                        cat	                Displays the contents of a file	                cat file.txt
    System Information	                whoami	            Shows the current logged-in user	            whoami
                                        uname	            Displays system information	                    uname -a
                                        df	                Shows disk space usage                         	df -h
                                        free	            Displays memory usage	                        free -m
    File Permissions                	chmod	            Changes file permissions	                    chmod script.sh
                                        chown	            Changes file ownership	                        chown user:group file.txt
    Process Management	                ps	                Lists running processes	                        ps aux
                                        kill	            Terminates a process by PID	                    kill 
                                        top	                Displays real-time system processes	            top
    Search/Text Processing	            grep	            Searches for text patterns in files         	grep "error" logfile.txt
                                        find	            Searches for files/directories              	find / -name "myfile.txt"
                                        wc	                Counts lines, words, or characters in a file    wc -l file.txt
    Package Management	                apt	                Manages packages (Debian/Ubuntu)	            sudo apt update
    Miscellaneous	                    echo	            Prints text to the terminal	                    echo "Hello, World!"
                                        man	                Displays the command manual	                    man ls
                                        sudo	            Runs a command as a superuser	                sudo apt update
                                        
                                        