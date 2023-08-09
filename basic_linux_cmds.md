## Top basic commands in Linux
Commands | Options/Syntax | Descriptions
--- | --- | ---
**help**|`cmd --help` | *it will disply all options for that cmd*
**man**|`man cmd` | *it will display manual for that cmd*
^ | `^` | *represent start of the word*
| | `ll ^devops` |  *list the file whose name start from devops*
$ | `$` | `$` *represent end of the word*
| | `ll txt$` | *list the files whose name ends with txt*
`*` | `*` | *in linux `*` means everything present on that location*
| | `du -sh *` | *calculate size of all folder and file*
**echo** |  | *date command print user input*
| | `echo "Hi DevOps"`| *print user input as it is*
**pwd** |  | *pwd command print present working directory*
**date** |  | *date command print date and time*
| |`date` | *date command print date and time*
| | `date +%Y`| *print year*
| | `date +%m`|*print month*
| | `date +%d`| *print date*
| | `date +%Y-%m-%d` | *print full date like 2022-01-05*
| | `date +%H`| *print hour*
| | `date +%M`|*print Minute*
| | `date +%S`| *print Second*
| | `date +%H:%M:%S` | *print time  11:12:13*
| | `date +%A`| *print day like Wednesday*
| | `date +%B`|*print month like January*
uname| | *uname gives os related information*
| | `uname -a` | *it print all os related information*
| | `uname -r` | *print kernel version*
| | `uname -s`| *print kernel name*
| | `uname -p` |*print processor name*
uptime |`uptime` | *it print uptime of server*
who |`who` | *it print login user information in short*
w |`w` | *it print login user information in details*
last|`last`|*it print all login history and last reboot performed by user*
ip | `ip r` | *it display the server ip*
hostname | `hostname` | *it display the name of the server*
free |  | *it give memory related information*
| | `free` | *print memory stats in bytes*
| | `free -m` | *print memeory stats in MB*
| | `free -g` | *print memeory stats in GB*
| | `free -h` | *print memeory stats in human readable form*
df | | *print disk related stats*
| | `df`|*print disk stats in bytes*
| | `df -h`|*print disk stats in human readable form*
clear| `clear  or ctrl +l` | *clear terminal*
wget| |*wget cmd usd t download content from internet*
| | `wget  download-link` | *wget cmd usd t download content from internet* 
du | | *find disk usage*
| |`du -sh *` | *print size of all files and folder where you run the cmd*
ping | | *this cmd is used to check connectivity with destination*
cmd;cmd | `;` |*`;` allow you to run multiple command at a same time*
| | `free -h;df -h`|*print memory & disk stats*
logout/exit | `logout   or ctrl +d` | *you can logout from user*
**which**|`which cat` | *print the full path of argument*
history |`history` |*it will display history of all cmds run by user*
