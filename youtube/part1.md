# Bash Scripting 1 

it's bash + programming

# Bash Scripting 2

word count program for counting line in a file
```
$ wc -l < 'filename'
$ cat testfile | wc -l
```
Conditional execution: adding command, but the first has to be done
```
$ (cat testfile | wc -l) && echo "Done!"
```
Conditional execution: or
```
$ ls wdwdsasdokw || echo "Success!"
```

# Bash Scripting 3

bash punya beberapa variable bawaan
```
$ my_var="This is wonderful"
$ some_number=6
```
untuk nama var, kalo ada 2 kata atau lebih maka disatukan dengan _
jangan ada space ya

Echo variable
```
$ echo "My favorite number is $some_number"
```
Echo command
```
$ echo "There are `cat testfile | wc -l` lines here"
```
