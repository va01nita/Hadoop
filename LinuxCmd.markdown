#  Basic Linux Commands
#### Who:
    shows who logged on in detail

#### Whoami:
    shows username who logged on

#### sudo su <username>:
    switch user

#### exit:
    exits from user back

#### uname:
    print certain system information

#### uptime:
    shows time since system is switched on

#### date: 
    displays date with day and time & timezone

#### cd <dir>:
    to change directory

#### cd ..:
    to go previous or down by one level

#### cd -:
    to go to home level

#### cp <src> <destn>:
    for copy purpose


#### cat <filename>:
    to see contents of the specified file

#### cat <filename1> > <filename2>:
    copies contents of the specified file1 into file2

#### cat <filename> >> <filename2>:
    appends contents of the specified file1 into file2

#### ls: 
    to display files in present dir

#### ll:
    to display all the files with hidden also in present dir. Following info also displayed:
    -Filetype
    -user permissions
    -group permissions
    -owner/other permisions
    -no of hard links to file
    -file owner
    -file group
    -file size
    -date and time
    -file name

#### ll >filename:
    copies selected portion from terminal to specified filename

#### mkdir:
    to create new directory

#### pwd:
    present working directory

#### rmdir <dirname> -r:
    removes empty directory completely (r-recursive) 

## rm <filename>/<dirname>:
    removes file/directory even if not empty
    -r: removes dir with child dir
    -rf: removes without taking permission before
    -i: removes by taking permission before

## mkdir -p A/B/C/1:
    -p: no error if exists and creates parent with child directories
    makes directory structure as given

#### nano <filename>:
    opens/creates file with editor in terminal

### ls-ltr:
    -l: uses long listing format
    -t: sort by time, newest first
    -r: reverse order while sorting

### touch <filename>:
    creates empty file
### tac <filename>:
    writes each file to std output,last line first
#### tree:
     defines/desplays tree structure of the directory
#### sudo apt-get install:
    to install package/software/command/etc


## **Cluster management can be done if data is too big to handle; using these techiques
1. By compressing the data
2. Moving data to cloude based services like Azure/AWS
3. By quota management techniques

### tar cvf new_file_name fileTobeCompressed:
    To compress the specified file
### tar xvf fileTobeDecompresed:
    To extract contents of tar file
### tar xvf fileTobeDecompresed -C /pathWhereToExtractFile:
    To extract contents of tar file at specified location
### tar zcvf filename.tar.gz fileTobeCompresed:
    To compress contents of the file
### tar zxvf fileTobeDecompresed:
    To extract contents of tar.gz file
### zip file.zip file/pathTobecompresed:
    To compress contents of the file
### unzip filename.zip -d path:
    To extract contents of zipped file at path/location
### du -h filename:
    To check size of file

