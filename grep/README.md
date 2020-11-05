# grep

grep [options] pattern [files]  
Options Description  
-c : This prints only a count of the lines that match a pattern  
-h : Display the matched lines, but do not display the filenames.  
-i : Ignores, case for matching  
-l : Displays list of a filenames only.  
-n : Display the matched lines and their line numbers.  
-v : This prints out all the lines that do not matches the pattern  
-e exp : Specifies expression with this option. Can use multiple times.  
-f file : Takes patterns from file, one per line.  
-E : Treats pattern as an extended regular expression (ERE)  
-w : Match whole word  
-o : Print only the matched parts of a matching line,  
with each such part on a separate output line.

#### Video Tutorial: Linux/Mac Terminal Tutorial: The Grep Command - Search Files and Directories for Patterns of Text

https://www.youtube.com/watch?v=VGgTmxXp7xQ

## Print all lines containing specific characters

#### Syntax

```
grep -i "<string>" <filename>
```

#### file

Cat is smaller than elephant  
Elephant is larger than cat  
Cats are cute!  
Elephants are very strong  
Cat and elephants live in different environments  
cats are friendly

#### command

```
grep -i "cat" file | grep -i "elephant"
```

#### output

Cat is smaller than elephant  
Elephant is larger than cat  
Cat and elephants live in different environment
