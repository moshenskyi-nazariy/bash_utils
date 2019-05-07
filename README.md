# Bash utils

Here are my bash utils, such as file sorter, clipboard copier, etc.


## 1. copy
___
This utility is made for easier copying file paths, outputs, etc.

### Setup guide:

* Add `copy` file to your `/usr/bin/local`: `sudo mv YOUR_FOLDER/copy /usr/bin/local`.
* Go to `/usr/bin/local`.
* Add this script an execute rule: `chmod +x copy`

**Optional part:**

* Open your `.bashrc`: `gedit ~/.bashrc`
* At the very bottom of your file add alias: `alias copy='/usr/local/bin/copy'`
* Save and exit `.bashrc`
* Update `.bashrc`: `source ~/.bashrc`

### Usage guide

* Copy the content of your file: `copy abc.txt` or `/usr/local/bin/ abc.txt`
* Copy your present working directory: `pwd | copy` or `pwd | /usr/local/bin/`

___

## 2. fnamer

This utility sorts files in your `~/Downloads` folder by subfolders.

### Setup guide:

* Add `fnamer` file to your `/usr/bin/local`: `sudo mv YOUR_FOLDER/fnamer /usr/bin/local`.
* Go to `/usr/bin/fnamer`.
* Add this script an execute rule: `chmod +x fnamer`

**Optional part:**

* Open your `.bashrc`: `gedit ~/.bashrc`
* At the very bottom of your file add alias: `alias copy='/usr/local/bin/fnamer'`
* Save and exit `.bashrc`
* Update `.bashrc`: `source ~/.bashrc`
### Usage guide

Just run the script: `fnamer` or `/usr/local/bin/fnamer` and it will sort your files by subfolders.
