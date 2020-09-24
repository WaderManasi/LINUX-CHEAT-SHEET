### :gem: LINUX CHEATSHEET 

*:ballot_box_with_check: Let's Hands-on the Linux Commands for working on Super Useful and Powerful Linux Command Line Interface (CLI)* :round_pushpin:

## /********************** :o: LINUX SYSTEM COMMANDS :o: *********************************/ 

-sudo                          :short name for "SuperUser Do" enables to perform tasks which require administrative or root permissions
-ls                            :list of directories
-stat                          :details of inode
-gcc file_name.c -o myexe      :create object file while compilation and create separate excecutable
-mkdir                         :make new directory
-rmdir                         :remove directory
-rm                            :remove file
-touch                         :create new file
-make                          :runs the makefile (makefile: used to manage project)
-cd                            :enter into directory
-cp                            :copy files from current directory to diff directory
-pwd                           :prints current working directory
-cat file_name                 :list the contents of file
-mv file_name source dest      :move file from source to destination
-find                          :searches for the files and directories
-df                            :to get report of system disk space usage (in % and kb)
-df -m                         :to get report of system disk space usage (in mb)
-du                            :to check space used by file or directory (in blocks)
-du -h                         :to check space used by file or directory (in bytes, kb and mb)
-tar                           :used to archieve multiple files
-chmod                         :to change read, write and execute permissions of file or directory
-ping                          :to check connectivity status (ping google.com)
-wget                          :to download required data from internet (eg wget download_link)
-uname                         :nothing but stands for Unix Name (tells the unix type you are using)
-history                       :gives list of commands used by you on terminal till date
-zip                           :zip multiple files
-unzip                         :unzip the zip folder
-clear                         :to clean out the terminal with all past commands (but it is still there in history)



## /*********************** :o: LINUX SHUTDOWN COMMANDS :o: *********************************/ 

-shutdown -h now               :immediately power off & shutdown the system 
-shutdown -h +5                :shutdown the system after 5 minutes
-shutdown -r now               :reboot the system 
-shutdown -Fr now              :force file system check during reboot

## /*********************** :o: LINUX FUNCTIONS :o: *********************************/

stat(file_name,address of stat object)            :gives information about file
access(file_name,mode_of_permission)              :return positive int if process has access of the requested mode/mode_of_permission
opendir()                                         :directory file handling
readdir()                                         :read contents of directory (data cannot be written in directory)
