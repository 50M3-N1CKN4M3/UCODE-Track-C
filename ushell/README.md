<head>
    <p align="center">
        <a href="https://ucode.world/en/" target="_blank">
            <img src="https://github.com/PAXANDDOS/PAXANDDOS/blob/main/Images/Header/ucode.png?raw=true" height="100px">
        </a>
        <a href="https://unitfactory.net/" target="_blank">
            <img src="https://github.com/PAXANDDOS/PAXANDDOS/blob/main/Images/Header/unit.png?raw=true" height="100px">
        </a>
        <a href="https://lms.ucode.world/users/plitovka/" target="_blank">
            <img src="https://github.com/PAXANDDOS/PAXANDDOS/blob/main/Images/Header/lms.png?raw=true" height="100px">
        </a>
    </p>
</head>

## Building the program
<ol>
    <li>Download the source code from this repository.</li>
    <li>Go to the program directory.</li>
    <li>Run <code>make</code> in terminal.</li><br>
</ol>
<b>Attention! This program only works with OSX systems!</b>

## Usage
`ush`<br>
For example: `./ush`<br>
You will get into our shell `u$h>` and then you can use all its functionality. 

## Functionality
<b>Browse through your directories with ```cd``` command.</b> You can alse use it with flags:
* ```-s``` to browse silently.
* ```-P``` use the physical directory structure without following symbolic links: resolve symbolic links in DIR before processing instances of `..'.
* ```-``` to go to the previously entered directory.

<br><b>See the absolute pathname of the current working directory by using ```pwd``` command.</b> You can alse use it with flags:
* ```-L``` to display the logical current working directory.
* ```-P``` to display the physical current working directory (all symbolic links resolved). If no options are specified, the -P option is assumed.

<br><b>Write arguments to the standard output with ```echo``` command.</b> You can alse use it with flags:
* ```-n``` to do not append a newline.
* ```-e``` to enable interpretation of the following backslash escapes.
* ```-E``` to explicitly suppress interpretation of backslash escapes.

<br><b>View the full path of shell commands by using ```which```.</b> You can alse use it with flags:
* ```-a``` to list all instances of executables found (instead of just the first one of each).
* ```-s``` No output, just return 0 if all of the executables are found, or 1 if some were not found.

<br><b>Set environment for command invocation with ```env``` command.</b> You can alse use it with flags:
* ```-i``` to start with an empty environment.
* ```-P``` to search the set of directories as specified by altpath to locate the specified utility program.
* ```-u``` to remove variable from the environment.

<br><b>Set export attribute for shell variables with ```export``` command.</b>  
<br><b>Unset values and attributes of variables and functions with ```unset``` command.</b>  
<br><b>Exit ush with ```exit``` command.</b>  
<br><b>Resume the specified job in the foreground, and make it the current job with ```fg``` command.</b>  
<br><b>Resume the specified job in the foreground, and make it the current job with ```fg``` command.</b>  
<br><b>All signals are managed correctly: ```CTRL+D```, ```CTRL+C``` and ```CTRL+Z```</b>  
<br><b>Also managed:</b> 
* the tilde expansion ```~```  with the following tilde-prefixes: ```~``` , ```~/dir_name```, ```~username/dir_name```, ```~+/dir_name```, ```~-/dir_name```  
* the basic form of parameter expansion ```${parameter}```
* the two-level-nested command substitution ```$(command)```
* many types of errors
* implementation the command separator ```;``` 

<br><b>User allowed to customize prompt and to make it unique and useful e.g. ```show current directory```, ```git info```, etc.</b>  
<br><b>Many keys and commands are also supported:</b>
* implementation of command editing. Moving the cursor using the ```Arrow keys``` or the ```HOME``` and ```END``` keys.
* support of command history. Sequential search e.g. with ```Page Up``` and ```Page Down``` keys. Or query search with ```CTRL+R```.
* implementation of the ```fg```  builtin command without arguments and with arguments, for example, ```%n```, ```%str```.
* implementation of multiline user input.
* support of the nested command substitution ```command``` and ```$(command)```.
* support of shell functions ```tripple_ls() { ls; ls; ls; }```.
* implementation of auto-completion using the ```TAB``` key.
* support of pipes ```|```
* support of redirecting output ```>```, ```<```, ```>>```, ```<<```.
* support of logical operators ```&&```  and ```||```.
* support of aliases.

## Authors
<p align="center">
    <a href="https://github.com/PAXANDDOS" target="_blank"><img src="https://github.com/PAXANDDOS/PAXANDDOS/blob/main/Images/Banners/paxanddos.png?raw=true" height="75px"></a>
    <a href="https://github.com/dullylol" target="_blank"><img src="https://github.com/PAXANDDOS/PAXANDDOS/blob/main/Images/Banners/lesha.png?raw=true" height="75px"></a>
</p>
<p align="center">
    <a href="https://github.com/XIZORG" target="_blank"><img src="https://github.com/PAXANDDOS/PAXANDDOS/blob/main/Images/Banners/jeka.png?raw=true" height="75px"></a>
</p>
