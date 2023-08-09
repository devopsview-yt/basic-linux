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
| | `TZ=IST-5:30 date` |*print date and time in IST*
**cal** |`cal` | *display calender*
| | `cal -y` |*display 12 months calender*
| | `cal -3` |*display 3 months*
**which**|`which cat` | *print the full path of argument*
uname| | *uname gives os related information*
| | `uname -a` | *it print all os related information*
| | `uname -r` | *print kernel version*
| | `uname -s`| *print kernel name*
| | `uname -p` |*print processor name*
uptime |`uptime` | *it print uptime of server*
last|`last`|*it print all login history and last reboot perform by user*
users | `users` | *it display the users name*
ip | `ip r` | *it display the server ip*
/etc/bashrc | `vim /etc/bashrc` |*change the server name*
hostname | `hostname` | *it display the name of the server*
free |  | *it give memory related information*
| | `free` | *print memory stats in bytes*
| | `free -m` | *print memeory stats in MB*
| | `free -g` | *print memeory stats in GB*
| | `free -h` | *print memeory stats in human readable form*
df | | *print disk related stats*
| | `df`|*print disk stats in bytes*
| | `df -h`|*print disk stats in human readable form*
wc | | *print number of line character and word count of file*
| | `wc -l` | *print number of lines file has*
| | `wc -c` | *print number of characters file has*
| | `wc -w` | *print number of words file has*
history |`history` |*it will display history of all cmds run by user*
clear| `clear  or ctrl +l` | *clear terminal*
du | | *find disk usage*
| |`du -sh *` | *print size of all files and folder where you run the cmd*
wget| |*wget cmd usd t download content from internet*
| | `wget  download-link` | *wget cmd usd t download content from internet* 
ping | | *this cmd is used to check connectivity*
cmd;cmd | `;` |*`;` allow you to run multiple command at a time*
logout/exit | `logout   or ctrl +d` | *you can logout from user*
nslookup | `nslookup devopsview.com` | *it will print ip behind this website*
alias |`alias c='clear'` | *alias is shortcut of particular cmd*
.bash_profile | | *this file execute at user login*
.bash_logout | | *this file execute at user logout*
