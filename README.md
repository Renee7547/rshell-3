#rshell
rshell is an imitation of the BASH terminal. This implementation allows the use 
of connectors such as `||`, `&&` and `;`.  Anything after a `#` is a comment and 
is ignored by the program. The command `exit` closes the program. 

Connector Meanings:
`||` run command only if first one fails.
`&&` run command only if first one succeeds.
`;` run any command if the command is true.

#How to run rshell
```
$git clone https://github.com/jmeji011/rshell.git
$cd rshell
$git checkout hw0
$make
$bin/rshell
```

#Bugs
Echo with quotes do not work with this shell implementation.

`echo "hello"` , This will display `"hello"`. 

#LS
This program imitates the ls command found in the bash terminal.
This program can handle the following flags after calling ls:
`-l`, `-a`, `-R`
It can also handle the flags when they are combined.

#How to run ls
```
$git clone https://github.com/jmeji011/rshell.git
$cd rshell
$git checkout hw1
$make
$bin/ls
```
#LS Bugs
The directories and filenames are not aligned during use of standard ls in comparison
to bashs ls. 



