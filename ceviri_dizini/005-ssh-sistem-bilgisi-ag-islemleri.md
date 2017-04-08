## 1.4. SSH, System Info & Network Operations

<table>
   <tr>
      <td><a href="#a-bg">bg</a></td>
      <td><a href="#b-cal">cal</a></td>
      <td><a href="#c-date">date</a></td>
      <td><a href="#d-df">df</a></td>
      <td><a href="#e-dig">dig</a></td>
      <td><a href="#f-du">du</a></td>
      <td><a href="#g-fg">fg</a></td>
      <td><a href="#h-finger">finger</a></td>
      <td><a href="#i-kill">kill</a></td>
      <td><a href="#j-killall">killall</a></td>
   </tr>
   <tr>
      <td><a href="#k-last">last</a></td>
      <td><a href="#l-man">man</a></td>
      <td><a href="#m-passwd">passwd</a></td>
      <td><a href="#n-ping">ping</a></td>
      <td><a href="#o-ps">ps</a></td>
      <td><a href="#p-quota">quota</a></td>
      <td><a href="#q-scp">scp</a></td>
      <td><a href="#r-ssh">ssh</a></td>
      <td><a href="#s-top">top</a></td>
      <td><a href="#t-uname">uname</a></td>
   </tr>
   <tr>
      <td><a href="#u-uptime">uptime</a></td>
      <td><a href="#v-w">w</a></td>
      <td><a href="#w-wget">wget</a></td>
      <td><a href="#x-whoami">whoami</a></td>
      <td><a href="#y-whois">whois</a></td>
   </tr>
</table>

### a. `bg`
Lists stopped or background jobs; resume a stopped job in the background.

### b. `cal`
Shows the month's calendar.

### c. `date`
Shows the current date and time.

### d. `df`
Shows disk usage.

### e. `dig`
Gets DNS information for domain.  
```bash
dig domain
```

### f. `du`
Shows the disk usage of files or directories. For more information on this command check this [link](http://www.linfo.org/du.html)
```bash
du [option] [filename|directory]
```
Options:
- `-h` (human readable) Displays output it in kilobytes (K), megabytes (M) and gigabytes (G).
- `-s` (supress or summarize) Outputs total disk space of a directory and supresses reports for subdirectories. 

Example:
```bash
du -sh pictures
1.4M pictures
```

### g. `fg`
Brings the most recent job in the foreground.

### h. `finger`
Displays information about user.  
```bash
finger username
```

### i. `kill`
Kills (ends) the processes with the ID you gave.  
```bash
kill PID
```

### j. `killall`
Kill all processes with the name.  
```bash
killall processname
```

### k. `last`
Lists your last logins of specified user.  
```bash
last yourUsername
```

### l. `man`
Shows the manual for specified command.  
```bash
man command
```

### m. `passwd`
Allows the current logged user to change his password.

### n. `ping`
Pings host and outputs results.  
```bash
ping host
```

### o. `ps`
Lists your processes.  
```bash
ps -u yourusername
```

### p. `quota`
Shows what your disk quota is.  
```bash
quota -v
```

### q. `scp`
Transfer files between a local host and a remote host or between two remote hosts.

*copy from local host to remote host*
```bash
scp source_file user@host:directory/target_file
```
*copy from remote host to local host*
```bash
scp user@host:directory/source_file target_file
scp -r user@host:directory/source_folder farget_folder
```
This command also accepts an option `-P` that can be used to connect to specific port.  
```bash
scp -P port user@host:directory/source_file target_file
```

### r. `ssh`
ssh (SSH client) is a program for logging into and executing commands on a remote machine.  
```bash
ssh user@host
```
This command also accepts an option `-p` that can be used to connect to specific port.  
```bash
ssh -p port user@host
```

### s. `top`
Displays your currently active processes.

### t. `uname`
Shows kernel information.  
```bash
uname -a
```

### u. `uptime`
Shows current uptime.

### v. `w`
Displays who is online.

### w. `wget`
Downloads file.  
```bash
wget file
```

### x. `whoami`
Return current logged in username.

### y. `whois`
Gets whois information for domain.  
```bash
whois domain
```

