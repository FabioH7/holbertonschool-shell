#Shell scripting, how to and a simplified look at it.

> Shell is one of the most used coding languages in the world because of it's easy to learn and hard to master learning style.
In shell you can execute plenty of cool commands and if you know all the separate components individually it is fairly satisfying to make a cool looking commands. __I would always recommend shell as a starting coding language.__

* Executing a command in shell can be done in 2 ways
> __Either you execute it on the main terminal which is nice for beginners, but when needing to execute multiple commands at the same time or if you want command shortcuts you will probably want to use a script.__ 

* Scripting is the execution of a command from a created file. 

_In simpler terms it is the same thing as writing a command from the terminal but it is made in a file._
* To execute a command you first make a file and then open it using either vi, emacs or vim.
* Afterwards you will need to write a command to connect your file to the directory where your commands are by typing the following:

```shell
> #!/bin/bash
```
Under the former you can write your desired command like this:
```shell
> cd /root/hello/hi
```   
* After you have typed the command save the changes and then you want to make sure that the terminal recognises your file by typing the following:
```shell
> chmod u+x <filename>
```  
* This command notifies the system that this file has an executable command. To execute it write the following:
```shell
> ./<filename>
```

### If done correctly you should see the  command has executed, if so congrats you are now a scripter.

> You can experiment with this any way you want, either by typing other commands like:
```shell
> cd
```
* Beware that when accessing the root directory to execute a command like cd, you must write the  following change to your execution command:
```shell
> source ./<filename>
```

This accesses the main root file which allows you to access previous directories and switch between them.

> In conclusion shell scripting at most allows you to make highly advanced scripts and execute them quickly and at worst allows the user to make shortcuts of commands.

* So it's pretty neat! :)
