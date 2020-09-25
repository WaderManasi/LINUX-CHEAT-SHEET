### :gem: LINUX CHEATSHEET 

*:ballot_box_with_check: Let's Hands-on the Linux Commands for working on Super Useful and Powerful Linux Command Line Interface (CLI)* :cyclone:

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
- <b>rm -rf .git </b>                  :to remove hidden .git folder in linux


#### *********************** :o: LINUX SHUTDOWN COMMANDS :o: *********************************

- <b>shutdown -h now</b>               :immediately power off & shutdown the system 
- <b>shutdown -h +5 </b>               :shutdown the system after 5 minutes
- <b>shutdown -r now</b>               :reboot the system 
- <b>shutdown -Fr now</b>              :force file system check during reboot

#### *********************** :o: LINUX FUNCTIONS :o: *********************************

- <b>stat(file_name,address of stat object)</b>            :gives information about file
- <b>lstat(file_name(path)),address of stat object)</b>    :same as stat() but for symbolic links/soft links it returns info of link iself instead of target file
- <b>fstat(file_descriptor,address of stat object)</b>     :gives metadata
- <b>access(file_name,mode_of_permission)</b>              :return positive int if process has access of the requested mode/mode_of_permission
- <b>opendir()</b>                                         :directory file handling
- <b>readdir()</b>                                         :read contents of directory (data cannot be written in directory)
- <b>closedir()</b>                                        :close the opened directory
- <b>chmod(path,mode)(</b>                                             :system call to change the file permisssions mode
- <b>fchmod(file_descriptor,mode)</b>                                             :system call to change the file permisssions mode
