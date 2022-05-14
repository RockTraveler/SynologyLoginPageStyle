### English | [中文](https://github.com/RockTraveler/SynologyLoginPageStyle/blob/main/README_ZH.md)

# SynologyLoginPageStyle

## Introduction

This project create for sysnology device login page updating, the css file has ability to update the login panel to be more beautiful.

### Note
This css script updated base on DSM 7.0 that will be not take effect before DSM 7.0

## How to Use

1. Download the css file.
2. Login into your synology device via SSH protocol, that requires your root privilege to update your css file.
3. and put the css file under the directory: /usr/syno/synoman/webman/login/css, please also backup your css file before overwrite.
4. Update file name login.css.gz to another such as login.css.gz_bak.
5. try to reload your browser and enjoy it.


## Relevant Commands 

1. change directory to /usr/syno/synoman/webman/login/css:  cd /usr/syno/synoman/webman/login/css
2. switch current user to root privilige that requires your root privilige: sudo -i
3. backup your file: mv filename mv filename_bak
4. put your file into /usr/syno/synoman/webman/login/css: cp /some path/filename /usr/syno/synoman/webman/login/css
5. Update file name login.css.gz to another: mv login.css.gz login.css.gz_bak



## Example:

### Before update
![image](https://github.com/RockTraveler/SynologyLoginPageStyle/blob/main/example/before.png)

### After update

![image](https://github.com/RockTraveler/SynologyLoginPageStyle/blob/main/example/after.png)
