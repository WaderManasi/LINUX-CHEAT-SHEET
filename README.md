### :gem: LINUX CHEATSHEET 

*:ballot_box_with_check: Let's Hands-on the Linux Commands for working on Super Useful and Powerful Linux Command Line Interface (CLI)* :round_pushpin:

#### ********************** :o: LINUX SYSTEM COMMANDS :o: *********************************

- <b>sudo</b>                          :short name for "SuperUser Do" enables to perform tasks which require administrative or root permissions
- <b>ls</b>                            :list of directories
- <b>stat</b>                          :details of inode
- <b>gcc file_name.c -o myexe</b>      :create object file while compilation and create separate excecutable
- <b>mkdir</b>                         :make new directory
- <b>rmdir</b>                         :remove directory
- <b>rm</b>                            :remove file
- <b>touch</b>                         :create new file
- <b>make</b>                          :runs the makefile (makefile: used to manage project)
- <b>cd</b>                            :enter into directory
- <b>cp</b>                            :copy files from current directory to diff directory
- <b>pwd</b>                           :prints current working directory
- <b>cat file_name</b>                 :list the contents of file
- <b>mv file_name source dest</b>      :move file from source to destination
- <b>find</b>                          :searches for the files and directories
- <b>df</b>                            :to get report of system disk space usage (in % and kb)
- <b>df -m</b>                         :to get report of system disk space usage (in mb)
- <b>du</b>                            :to check space used by file or directory (in blocks)
- <b>du -h</b>                         :to check space used by file or directory (in bytes, kb and mb)
- <b>tar</b>                           :used to archieve multiple files
- <b>chmod</b>                         :to change read, write and execute permissions of file or directory
- <b>ping</b>                          :to check connectivity status (ping google.com)
- <b>wget</b>                          :to download required data from internet (eg wget download_link)
- <b>uname</b>                         :nothing but stands for Unix Name (tells the unix type you are using)
- <b>history</b>                       :gives list of commands used by you on terminal till date
- <b>zip</b>                           :zip multiple files
- <b>unzip</b>                         :unzip the zip folder
- <b>clear</b>                         :to clean out the terminal with all past commands (but it is still there in history)



#### *********************** :o: LINUX SHUTDOWN COMMANDS :o: *********************************

- shutdown -h now               :immediately power off & shutdown the system 
- shutdown -h +5                :shutdown the system after 5 minutes
- shutdown -r now               :reboot the system 
- shutdown -Fr now              :force file system check during reboot

#### *********************** :o: LINUX FUNCTIONS :o: *********************************

- stat(file_name,address of stat object)            :gives information about file
- access(file_name,mode_of_permission)              :return positive int if process has access of the requested mode/mode_of_permission
- opendir()                                         :directory file handling
- readdir()                                         :read contents of directory (data cannot be written in directory)
