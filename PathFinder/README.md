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
        <h2 align="center">Pathfinding is very imporant thing. This is my repo for UCODE Pathfinder.</h2>
    </p>
</head>

## Building the program
<ol>
    <li>Download the source code from this repository</li>
    <li>Go to the program directory</li>
    <li>Run <code>make</code> in terminal</li><br>
</ol>
<b>Attention! This program only works with OSX systems</b>

## Usage
`./pathfinder [filename]`<br>
For example: `./pathfinder test/example2`

## Example
###  Source file (test/example2)
```
5
A-B,11
A-C,10
B-D,5
C-D,6
C-E,15
D-E,4
```
###  Output
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
## Error handling
The program also handles all possible errors declared in the assignment.
### Error: file [filename] does not exist
<code>PAXANDDOS% ./pathfinder test/bruh</code><br>
<code>error: file test/bruh does not exist</code>

### Error: file [filename] is empty
Source file: empty.   
Result:
```
PAXANDDOS% ./pathfinder test/bruh
error: file test/bruh does not exist
```

### Error: line 1 is not valid
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

### Error: line [line_number] is not valid
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

### Error: invalid number of islands
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

### Error: duplicate bridges
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

### Error: sum of bridges lengths is too big
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
<footer>
<p align="center"><img src="https://emojis.slackmojis.com/emojis/images/1531849430/4246/blob-sunglasses.gif?1531849430" width="30"></p>
<h4 align="center">Total mark for PathFinder is 100.</h4>
</footer>
