# CLI COMMAND NOTE
## Info
Summary of commands used in the _**Command Line Interface**_ 
> Note: Written based on Professor Jakeoung Koo’s Lecture 4

## Shell command
shows the current path in a hierarchical directory: 
```sh
pwd
```
change directory:
```sh
cd
```
list files and directories:
```sh
ls
```
More on ls...
| Command | Result |
| ------ | ------ |
| ls | List the files in the working directory |
| ls /bin | List the files in the _/bin_ directory (or any other directory we care to specify) |
| ls -l | List the files in the working directory in long format |
| ls -l /etc /bin | List the files in the _/bin_ directory and the _/etc_ directory in long format |
| ls -la .. | List all files in the parent of the working directory in long format |

## Tip
autocompletion: 
```sh
// Press "tab" key
```
past commands:
```sh
// Press "up arrow" key
```
clear:
```sh
clear
```
## Manipulatioion
copy files and directories:
```sh
cp
```
move files and directories or rename them:
```sh
mv
```
delete files and directories **permantely and irreversevely**:
```sh
rm
```
make a new directory:
```sh
mkdir
```

