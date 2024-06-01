# Linux Command Line

## Basic Commands

* **date:** current date

* **cal:** current months calendar

* **cal 1999:** calendar for 1999

* **cal -3:** calendar (last month, current and next month)

* **cal -y:** all year calendar

* **clear:** clear console text

* **exit:** exits de terminal

# Navigate Directories

## Linux File System Tree:

<img src="file.png">


* **bin:** binary (commands and utilities that all users can run)

* **sbin:** this directory contains programs that performs vital system tasks (network management, disk partitioning). Only the superuser has access to these programs.

* **home:** each user is given a directory under the home directory. A user can store anything in his home directory

* **opt:** optional (additional software)

* **tmp:** temporary files, files created by various programs (Generally cleared on reboot)

* **var:** variable data, data that frequently changes over time.

   * Log files

   * Data bases

   * User mail

   * Spools -> temporary storage location
/var/spool is traditionally used for machine-local data being spooled to or from UNIX subsystems. For example, print jobs are spooled here for delivery to the lineprinter daemon, out-bound mail is spooled for delivery to remote systems, and UUCP files are spooled for transmission to UUCP neighbors. In-bound mail and news are spooled here for delivery to users, and at and cron jobs are spooled for delayed execution by the cron daemon.




## Commands

* **pwd:** print working directory

* **ls:** list directory

* **cd:** change directory

* **cd /:** take you to the root directory

* **cd ~:** take you to the user home directory

* **cd ./another_folder:** navigate from current directory to another_folder

* **cd ..:** navigate from current directory to parent directory

* **cd -:** go back to the previous working directory

* **cd /:** going to the root directory

  * **cd ~/:** going to the home directory

  * **cd -:** going back to the root directory

  * **cd "my work"** or **cd 'my work'** or **cd my\ work:** going to a folder with space

* **ls /:** display your root directory

* **ls ~:** display your home directory

* **ls ..:** display the content of my parent directory

* **[DOES NOT WORK]** **ls -:** should display you the content of your previous working directory


# linux Links

* Every file in the system has an inode (Index node)

  * Contains all file information except the file content and name
  * A database of a file
  * They contain:

    * Inode number

    * File size

    * Owner information

    * Permission

    * File type

    * Number of links
    <br>

     * Soft Link
     * Hard Link
     
      * etc.....
