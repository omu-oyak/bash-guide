# 1. Basic Operations

### a. `export`
Displays all environment variables. If you want to get details of a specific variable, use `echo $VARIABLE_NAME`.  
```bash
export
```
Example:
```bash
$ export
AWS_HOME=/Users/adnanadnan/.aws
LANG=en_US.UTF-8
LC_CTYPE=en_US.UTF-8
LESS=-R

$ echo $AWS_HOME
/Users/adnanadnan/.aws
```

### b. `whereis`
whereis searches for executables, source files, and manual pages using a database built by system automatically.
```bash
whereis name
```
Example:
```bash
$ whereis php
/usr/bin/php
```

### c. `which`
which searches for executables in the directories specified by the environment variable PATH. This command will print the full path of the executable(s).
```bash
which program_name 
```
Example:
```bash
$ which php
/c/xampp/php/php
```

### d. clear
Clears content on window.

