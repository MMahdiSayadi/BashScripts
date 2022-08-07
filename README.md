# BashScripts
The Collection of scripts written in bash language

## some concepts 
what is the bash? BASH stands for Bourne Againe SHell. bash is basicaly the command line in the linux 
and we call it bash because it kind of wraps itself around the Linux kernel. shielding us from all the scary inner workings of Linux because honestly we probably couldn't handle it. 

So the bash shell is just how we make Linux do things. make new files, add new users hack.
it is also this crazy powerfull programming slash scripting language. let's write our first bash script right now. :)

## Requirements 
  * First : Linux !!!
  * Second: nano text editor

## what you have to do at first 

 * open a text file and write you scripts within it using nano editor. 

how to open nano: 
```
nano <script_name>.sh
if you see the permission denied type following command 
sudo nano <script_name>.sh
```

 * write some command line in it started by `!/bin/bash`
 * save it using hit `ctrl + x` followed by `y` and then press `enter`
now your file is been saved

the next thing who you have to do is to create your file executable: 
you can do this using following command: 
```
chmod +x <script_name>.sh 
```
it gives to your scripts executable permission.

 * as the final step you can run your programm using below command. 
 * `./<scripts_name>.sh`
