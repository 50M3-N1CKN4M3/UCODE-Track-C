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
<h3>Content:</h3>
<ul>
  <li><a href="#refresh-marathon-c">Refresh Marathon C</a></li>
  <li><a href="#libmx">Libmx - library of functions made during Marathon C</a></li>
  <li><a href="#pathfinder">Pathfinder - finding the shortest path from point to point</a></li>
  <li><a href="#uls">uls - implementation of UNIX utility "ls"</a></li>
  <li><a href="#ushell">ushell - implementation of UNIX shell</a></li>
  <li><a href="https://github.com/PAXANDDOS/PokeChat">uchat (PokéChat) - creating own messanger</a></li>
</ul>

<h1>Refresh Marathon C</h1>
<p>Date: October 2020<p>
<table width="100%" border="0" cellpadding="4" align="left">  
  <tr>
      <th>Name</th>
      <th>Description</th>
      <th>Grade</th>
  </tr>
  <tr>
      <th>Task00</th>
      <th>A function that outputs a single character to the standard output.</th>
      <th>100</th>
  </tr>
  <tr>
      <th>Task01</th>
      <th>A function that outputs the alphabet, alternating upper and lower case characters in ascending order.</th>
      <th>100</th>
  </tr>
  <tr>
      <th>Task02</th>
      <th>Standard functions and the basics of mathematics implementation in C.</th>
      <th>100</th>
  </tr>
  <tr>
      <th>Task03</th>
      <th>A function that outputs a string of characters.</th>
      <th>100</th>
  </tr>
  <tr>
      <th>Task04</th>
      <th>A function that outputs integer values.</th>
      <th>100</th>
  </tr>
  <tr>
      <th>Task05</th>
      <th>A function that computes 'n' raised to the power of zero or a positive integer 'pow'.</th>
      <th>100</th>
  </tr>
  <tr>
      <th>Task06</th>
      <th>A function that computes the non-negative square root of 'x'.</th>
      <th>100</th>
  </tr>
  <tr>
      <th>Task07</th>
      <th>A function that sorts an array of integers in ascending order.</th>
      <th>100</th>
  </tr>
  <tr>
      <th>Task08</th>
      <th>A function that has the same behaviour as the standard libc function strcmp.</th>
      <th>100</th>
  </tr>
  <tr>
      <th>Task09</th>
      <th>A function that has the same behaviour as the standard libc functionstrcpy.</th>
      <th>100</th>
  </tr>
  <tr>
      <th>Task10</th>
      <th>A functon that prints it's arguments.</th>
      <th>100</th>
  </tr>
  <tr>
      <th>Task11</th>
      <th>A functon that sorts it's arguments.</th>
      <th>100</th>
  </tr>
  <tr>
      <th>Task12</th>
      <th>A function that calculates the factorial of a non-negative integer using an iterative algorithm.</th>
      <th>100</th>
  </tr>
  <tr>
      <th>Task13</th>
      <th>A function that sorts an array of strings in place in lexicographical order using bubble sort.</th>
      <th>100</th>
  </tr>
  <tr>
      <th>Task14</th>
      <th>A function that searches the strings in the array arr with the given size using binary search.</th>
      <th>100</th>
  </tr>
  <tr>
      <th>Task15</th>
      <th>A function that allocates memory for a string of a specific size and one additional byte for theterminating '\0'</th>
      <th>100</th>
  </tr>
  <tr>
      <th>Task16</th>
      <th>A function that has the same behaviour as the standard libc function strdup.</th>
      <th>100</th>
  </tr>
  <tr>
      <th>Task17</th>
      <th>A function that converts a hexadecimal string into an unsigned long number.</th>
      <th>100</th>
  </tr>
  <tr>
      <th>Task18</th>
      <th>A function that applies the functionf  for each element of the array arr given size.</th>
      <th>100</th>
  </tr>
</table>

<h1 id="libmx">Libmx</h1>
<p>Date: October 2020</p>

### Utils pack
Function name|Description|Grade|
|-------------|----------------------------------------------------|---|
|```mx_printchar```|Prints single character on the standard output.|100|
|```mx_print_unicode```|Prints ASCII and multibyte characters on standard output.|100|
|```mx_printstr```|Prints string of characters on the standard output.|100|
|```mx_print_strarr```|Print array of strings.|100|
|```mx_printint```|Function that prints integer values on the standard output.|100|
|```mx_pow```|Function that computes ```n``` raised to the power of zero or positive integer ```pow``` .|100|
|```mx_sqrt```|Function that computes the non-negative square root of ```x``` . Function must compute square root in less than 2 seconds.|100|
|```mx_nbr_to_hex```|Function that converts an unsigned long number into a hexadecimal.|100|
|```mx_hex_to_nbr```|Function that converts a hexadecimal string into an unsigned long number.|100|
|```mx_itoa```|Function that takes an integer and converts it to a string.|100|
|```mx_foreach```|Function applies the function ```f``` for each element of the array ```arr``` of the given size.|100|
|```mx_binary_search```|Function that searches string ```s``` in array ```arr``` with the given size. Uses the binary search algorithm assuming that input array has already been sorted in lexicographical order.|100|
|```mx_bubble_sort```|Function that sorts an array of strings in place in exicographical order using bubble sort algorithm.|100|
|```mx_quicksort```|Function that sorts an array of strings by their length in ascending order using algorithm of quick sort. Pick middle element of the array as pivot. You must not check if ```left``` and ```right``` are correct.|100|

### String pack
Function name|Description|Grade|
|-------------|----------------------------------------------------|---|
|```mx_strlen```|Function that has the same behaviour as standard libc function ```strlen``` .|100|
|```mx_swap_char```|Function which will swap the characters of the string using pointers. Do nothing if ```s1``` or ```s2``` does not exist.|100|
|```mx_str_reverse```|Function which reverses string using pointers. Do nothing if string does not exist.|100|
|```mx_strdel```|Function that takes a pointer to string, then frees the string memory with ```free``` and sets string to ```NULL``` .|100|
|```mx_del_strarr```|Function that takes pointer to a NULL-terminated array of strings, deletes content of array, frees array memory with ```free``` and sets pointer to ```NULL``` .|100|
|```mx_get_char_index```|Function that finds index of the first occurrence of character ```c``` in a string str. String is a sequence of characters excluding the trailing ``` \0 ``` character.|100|
|```mx_strdup```|Function that has the same behaviour as standard libc function ```strdup``` .|100|
|```mx_strndup```|Function that has the same behaviour as standard libc function ```strdup``` .|100|
|```mx_strcpy```|Function that has the same behaviour as standard libc function ```strcpy``` .|100|
|```mx_strncpy```|Function that has the same behaviour as standard libc function ```strncpy``` .|100|
|```mx_strcmp```|Function that has the same behaviour as standard libc function ```strcmp``` .|100|
|```mx_strcat```|Function that has the same behaviour as standard libc function ```strcat``` .|100|
|```mx_strstr```|Function which has the same behaviour as standard libc function ```strstr``` .|100|
|```mx_get_substr_index```|Function that finds a index of substring.|100|
|```mx_count_substr```|Function that counts number of occurrences of substring in a string.|100|
|```mx_count_words```|Function which count words in the string. Word is a sequence of characters separated by delimiter.|100|
|```mx_strnew```|Function that: • allocates memory for a string of a specific ```size``` and one additional byte for terminating ``` '\0' ```  • initializes each character with ``` '\0' ``` • string of a specific size and terminated by ``` '\0' ```  • ```NULL``` if the creation fails..|100|
|```mx_strtrim ```|Function which creates new string without whitespace characters at the beginning and the end of the string and frees all unused memory with ```free ```.|100|
|```mx_del_extra_spaces ```|Function that creates new string without whitespace characters in the beginning and at the end of a string. It puts in the new string exactly one space character between words and frees all unused memory. Word is a sequence of characters separated by whitespaces.|100|
|```mx_strsplit ```|Function that converts a string ```s``` to the NULL-terminated array of words and frees all unused memory.|100|
|```mx_strjoin ```|Create a function concatenates strings s1 and s2 into new string and terminates new string with ``` '\0' ``` .|100|
|```mx_file_to_str ```|Function takes a filename as a parameter and then reads the data from file into the string.|100|
|```mx_replace_substr ```|Function that replaces all occurrences of ``` sub``` in ```str``` with ```eplace``` .|72|
|```mx_read_line ```||90|


### Memory pack
Function name|Description|Grade|
|-------------|----------------------------------------------------|---|
|```mx_memset```|Function that has the same behaviour as standard libc function ```memset``` .|100|
|```mx_memcpy```|Function that has the same behaviour as standard libc function ```memcpy``` .|100|
|```mx_memccpy```|Function that has the same behaviour as standard stdlib function ```memccpy``` .|100|
|```mx_memcmp```|Function that has the same behaviour as standard stdlib function ```memcmp``` .|100|
|```mx_memchr```|Function that has the same behaviour as standard stdlib function ```memchr``` .|100|
|```mx_memrchr```|The ```mx_memrchr``` function is like the ```mx_memchr``` function, except that it searches backwardfrom the end of the ```n``` bytes pointed to by ```s``` instead of forward from the beginning.|100|
|```mx_memmem```|Function that has the same behaviour as standard libc function memmem .|100|
|```mx_memmove```|Function that has the same behaviour as standard libc function ```memmove``` .|100|
|```mx_realloc```|Function that has the same behaviour as standard stdlib function ```realloc``` .|100|

### List pack
Function name|Description|Grade|
|-------------|----------------------------------------------------|---|
|```mx_create_node```|Function which creates a new node of linked list. Function must assign parameter ```data ```to the list variable ```data``` .|100|
|```mx_push_front```|Function that inserts a new node of ```t_list``` type with the given parameter ```data``` at the beginning of the linked list.|100|
|```mx_push_back```|Function that inserts a new node of ```t_list``` type with the given parameter ```data``` at the end of the linked list.|100|
|```mx_pop_front```|Function that removes the first node of the linked list and frees allocated for the node memory.|100|
|```mx_pop_back```|Function that removes the last node of the linked list and frees allocated for the node memory.|100|
|```mx_list_size```|Function that calculates the number of nodes in the linked list.|100|
|```mx_sort_list```|Function that sorts the list’s contents in ascending order. Function ``` cmp ``` returns true if ```a ``` > ``` b``` and false in other cases.|100|

<h1 id="pathfinder">Pathfinder</h1>
<p>Date: November 2020</p>

### Building the program
<ol>
    <li>Download the source code from this repository</li>
    <li>Go to the program directory</li>
    <li>Run <code>make</code> in terminal</li><br>
</ol>
<b>Attention! This program only works with OSX systems</b>

### Usage
`./pathfinder [filename]`<br>
For example: `./pathfinder test/example2`

### Example
####  Source file (test/example2)
```
5
A-B,11
A-C,10
B-D,5
C-D,6
C-E,15
D-E,4
```
####  Output
```
========================================
Path: A -> B
Route: A -> B
Distance: 11
========================================
========================================
Path: A -> C
Route: A -> C
Distance: 10
========================================
========================================
Path: A -> D
Route: A -> B -> D
Distance: 11 + 5 = 16
========================================
========================================
Path: A -> D
Route: A -> C -> D
Distance: 10 + 6 = 16
========================================
========================================
Path: A -> E
Route: A -> B -> D -> E
Distance: 11 + 5 + 4 = 20
========================================
========================================
Path: A -> E
Route: A -> C -> D -> E
Distance: 10 + 6 + 4 = 20
========================================
========================================
Path: B -> C
Route: B -> D -> C
Distance: 5 + 6 = 11
========================================
========================================
Path: B -> D
Route: B -> D
Distance: 5
========================================
========================================
Path: B -> E
Route: B -> D -> E
Distance: 5 + 4 = 9
========================================
========================================
Path: C -> D
Route: C -> D
Distance: 6
========================================
========================================
Path: C -> E
Route: C -> D -> E
Distance: 6 + 4 = 10
========================================
========================================
Path: D -> E
Route: D -> E
Distance: 4
========================================
```
### Error handling
The program also handles all possible errors declared in the assignment.
#### Error: file [filename] does not exist
<code>PAXANDDOS% ./pathfinder test/bruh</code><br>
<code>error: file test/bruh does not exist</code>

#### Error: file [filename] is empty
Source file: empty.   
Result:
```
PAXANDDOS% ./pathfinder test/bruh
error: file test/bruh does not exist
```

#### Error: line 1 is not valid
Source file: invalid1<br>
```
433f
Greenland-Bananal,8
Fraser-Greenland,10
Bananal-Fraser,3
Java-Fraser,5
```
Result:
```
PAXANDDOS% ./pathfinder test/bruh
error: file test/bruh does not exist
```

#### Error: line [line_number] is not valid
Source file: invalid2<br>
```
4
Greenland-Bananal,8
Fraser-Greenland,4
Bananal-Fraser,3
Java-Fraser,5
```
Source file: invalid3<br>
```
4
Greenland-Bananal,8
Fraser--Greenland,10
Bananal-Fraser,3
Java-Fraser,5
```
Result:
```
PAXANDDOS% ./pathfinder test/invalid2
error: line 6 is not valid
PAXANDDOS% ./pathfinder test/invalid3
error: line 3 is not valid
```

#### Error: invalid number of islands
Source file: invalid<br>
```
2
A-B,5
B-C,2
A-C,3
```
Result:
```
PAXANDDOS% ./pathfinder test/invalid
error: invalid number of islands
```

#### Error: duplicate bridges
Source file: duplicate<br>
```
4
A-B,11
A-C,10
B-C,5
B-C,6
```
Result:
```
PAXANDDOS% ./pathfinder test/duplicate
error: duplicate bridges
```

#### Error: sum of bridges lengths is too big
Source file: huge<br>
```
3
A-B,2147483647
A-C,2147483647
B-C,2147483647
```
Result:
```
PAXANDDOS% ./pathfinder test/huge
error: sum of bridges lengths is too big
```

<h1 id="uls">uls</h1>
<p>Date: October 2020</p>

### Building the program
<ol>
    <li>Download the source code from this repository.</li>
    <li>Go to the program directory.</li>
    <li>Run <code>make</code> in terminal.</li><br>
</ol>
<b>Attention! This program only works with OSX systems!</b>

### Usage
`uls [-ACGRSTcfglmortux1] [file ...]`<br>
For example: `./uls -l test`

#### Usable Flags
`-A`  List all entries except for . and ...  Always set for the superuser.  
`-C`  Force multi-column output; this is the default when output is to a terminal.  
`-G`  Makes output colorful and fancy.  
`-R`  Recursively list subdirectories encountered.  
`-S`  Sort files by size.  
`-T`  When used with the -l option, display complete time information for the file, including month, day, hour, minute, second, and year.  
`-c`  Use time when file status was last changed for sorting (-t) or long printing (-l).  
`-f`  Output is not sorted.  This option turns on the -a option.  
`-g`  This option is only available for compatibility with POSIX; it isused to display the group name in the long (-l) format output.  
`-l`  For each file, print the file's file serial number.  
`-m`  Stream output format; list files across the page, separated by commas.  
`-o`  List in long format, but omit the group id.  
`-r`  Reverse the order of the sort to get reverse lexicographicalorder or the oldest entries first (or largest files last, if combined with sort by size.  
`-t`  Sort by time modified (most recently modified first) before sorting the operands by lexicographical order.  
`-u`  Use time of last access, instead of last modification of the file for sorting (-t) or long printing (-l).  
`-x`  The same as -C, except that the multi-column output is produced with entries sorted across, rather than down, the columns.  
`-1`  Force output to be one entry per line.  This is the default when output is not to a terminal.  

### Authors
<p align="center"><a href="https://github.com/PAXANDDOS" target="_blank"><img src="https://github.com/PAXANDDOS/PAXANDDOS/blob/main/Images/Banners/paxanddos.png?raw=true" height="70px"></a>
<a href="https://github.com/Overwolf-live" target="_blank"><img src="https://github.com/PAXANDDOS/PAXANDDOS/blob/main/Images/Banners/ze.png?raw=true" height="70px"></a></p>

<h1 id="ushell">ushell</h1>
<p>Date: November 2020</p>

### Building the program
<ol>
    <li>Download the source code from this repository.</li>
    <li>Go to the program directory.</li>
    <li>Run <code>make</code> in terminal.</li><br>
</ol>
<b>Attention! This program only works with OSX systems!</b>

### Usage
`ush`<br>
For example: `./ush`<br>
You will get into our shell `u$h>` and then you can use all its functionality. 

### Functionality
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

### Authors
<p align="center">
    <a href="https://github.com/PAXANDDOS" target="_blank"><img src="https://github.com/PAXANDDOS/PAXANDDOS/blob/main/Images/Banners/paxanddos.png?raw=true" height="75px"></a>
    <a href="https://github.com/dullylol" target="_blank"><img src="https://github.com/PAXANDDOS/PAXANDDOS/blob/main/Images/Banners/lesha.png?raw=true" height="75px"></a>
</p>
<p align="center">
    <a href="https://github.com/XIZORG" target="_blank"><img src="https://github.com/PAXANDDOS/PAXANDDOS/blob/main/Images/Banners/jeka.png?raw=true" height="75px"></a>
</p>
