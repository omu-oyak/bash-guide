## 1.1. File Operations
<table>
   <tr>
      <td><a href="#a-cat">cat</a></td>
      <td><a href="#b-chmod">chmod</a></td>
      <td><a href="#c-cp">cp</a></td>
      <td><a href="#d-diff">diff</a></td>
      <td><a href="#e-file">file</a></td>
      <td><a href="#f-find">find</a></td>
      <td><a href="#g-gunzip">gunzip</a></td>
      <td><a href="#h-gzcat">gzcat</a></td>
      <td><a href="#i-gzip">gzip</a></td>
      <td><a href="#j-head">head</a></td>
   </tr>
   <tr>
      <td><a href="#k-lpq">lpq</a></td>
      <td><a href="#l-lpr">lpr</a></td>
      <td><a href="#m-lprm">lprm</a></td>
      <td><a href="#n-ls">ls</a></td>
      <td><a href="#o-more">more</a></td>
      <td><a href="#p-mv">mv</a></td>
      <td><a href="#q-rm">rm</a></td>
      <td><a href="#r-tail">tail</a></td>
      <td><a href="#s-touch">touch</a></td>
   </tr>
</table>

### a. `cat`
It can be used for the following purposes under UNIX or Linux.  
* Display text files on screen
* Copy text files  
* Combine text files  
* Create new text files  
```bash
cat filename
cat file1 file2 
cat file1 file2 > newcombinedfile
```

### b. `chmod`
Lets you change the read, write, and execute permissions on your files.  
```bash
chmod -options filename
```

### c. `cp`
Copies a file from one location to other.  
```bash
cp filename1 filename2
```
Where `filename1` is the source path to the file and `filename2` is the destination path to the file.

### d. `diff`
Compares files, and lists their differences.  
```bash
diff filename1 filename2
```

### e. `file`
Determine file type.  
```bash
file filename
```
Example:
```bash
$ file index.html
 index.html: HTML document, ASCII text
```
### f. `find`
Find files in directory
```bash
find directory options pattern
```
Example:
```bash
$ find . -name README.md
$ find /home/user1 -name '*.png'
```

### g. `gunzip`
Un-compresses files compressed by gzip.  
```bash
gunzip filename
```

### h. `gzcat`
Lets you look at gzipped file without actually having to gunzip it.  
```bash
gzcat filename
```

### i. `gzip`
Compresses files.  
```bash
gzip filename
```

### j. `head`
Outputs the first 10 lines of file  
```bash
head filename
```

### k. `lpq`
Check out the printer queue.  
```bash
lpq
```
Example:
```bash
$ lpq
Rank    Owner   Job     File(s)                         Total Size
active  adnanad 59      demo                            399360 bytes
1st     adnanad 60      (stdin)                         0 bytes
```

### l. `lpr`
Print the file.  
```bash
lpr filename
```

### m. `lprm`
Remove something from the printer queue.  
```bash
lprm jobnumber
```

### n. `ls`
Lists your files. `ls` has many options: `-l` lists files in 'long format', which contains the exact size of the file, who owns the file, who has the right to look at it, and when it was last modified. `-a` lists all files, including hidden files. For more information on this command check this [link](https://ss64.com/bash/ls.html).  
```bash
ls option
```
Example:
<pre>
$ ls -la
rwxr-xr-x   33 adnan  staff    1122 Mar 27 18:44 .
drwxrwxrwx  60 adnan  staff    2040 Mar 21 15:06 ..
-rw-r--r--@  1 adnan  staff   14340 Mar 23 15:05 .DS_Store
-rw-r--r--   1 adnan  staff     157 Mar 25 18:08 .bumpversion.cfg
-rw-r--r--   1 adnan  staff    6515 Mar 25 18:08 .config.ini
-rw-r--r--   1 adnan  staff    5805 Mar 27 18:44 .config.override.ini
drwxr-xr-x  17 adnan  staff     578 Mar 27 23:36 .git
-rwxr-xr-x   1 adnan  staff    2702 Mar 25 18:08 .gitignore
</pre>

### o. `more`
Shows the first part of a file (move with space and type q to quit).  
```bash
more filename
```

### p. `mv`
Moves a file from one location to other.  
```bash
mv filename1 filename2
```
Where `filename1` is the source path to the file and `filename2` is the destination path to the file.

Also it can be used for rename a file.
```bash
mv old_name new_name
```

### q. `rm`
Removes a file. Using this command on a directory gives you an error.
`rm: directory: is a directory`
To remove a directory you have to pass `-r` which will remove the content of the directory recursively. Optionally you can use `-f` flag to force the deletion i.e. without any confirmations etc.
```bash
rm filename
```

### r. `tail`
Outputs the last 10 lines of file. Use `-f` to output appended data as the file grows.  
```bash
tail filename
```

### s. `touch`
Creates or updates your file.  
```bash
touch filename
```
Example:
```bash
$ touch trick.md
```

