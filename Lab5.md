# CLI COMMAND NOTE (2)
## Info
Summary of commands used in the _**Command Line Interface**_ 
> Note: Written based on Professor Jakeoung Koo’s Lecture 5

## I/O Redirection
Displays the content of a text file:
```sh
cat
```
Redirect output using ">" after a command (e.g., ls) to create and save the output in a file. 
Example: 
```sh
ls -lh > file_list.txt
```
Using “>>” appends output to an extising file(if it already exitsts),or create and write to a new file if it doesn’t exist.
Example: 
```sh
ls -lh ›› file list.txt
```
Redirect input from a file using “<”.
Can mix “<“ and “>” together in a single line.
Example:
```sh
sort < words.txt > sorted words. txt
```

## Pipelines "|"
Pipeline feeds output of previous command to input of next command.
Example: 
```sh
1s -lh | less
```

## Expension
Special characters expand its meaning when given to shell commands.
Example: 
```sh
echo print out the text
echo *
echo ~
```

## Permisons
Change permision. Using 'chmod'.
Example:
```sh
chmod 600 README. md
```
More Info 
<img width="1064" alt="image" src="https://github.com/user-attachments/assets/4264dcae-d225-46de-98b7-273393acc566">

## Superuser
A superuser has all system administation authority. Using 'sudo'.
Example:
```sh
sudo some_command
```

## Text Editors
| Name | Interface |
| ------ | ------ |
| vi, vim | Commandline |
| Emacs | Commandline |
| nano | Commandline |
| gedit | graphical |
| kwrite | graphical |

## wget
download files from the internet directly to your active directory.
```sh
wget[URL]
```

## curl
curl:fetching, uploading, and managing data over the Internet.
```sh
curl[options][URL]
```
