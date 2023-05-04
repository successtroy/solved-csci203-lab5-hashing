Download Link: https://assignmentchef.com/product/solved-csci203-lab5-hashing
<br>
For this exercise, you are to implement a simple hash table.

As usual, your program will prompt for the name of an input file and the read and process the data contained in this file.

A sample file, ex5.txt, has been provided for test purposes.

The file contains a sequence of integer values. Read them and construct a hash table using chaining. For this exercise, you may use dynamic data for chains greater than one in length, but the majority of the dictionary should be an array of hash nodes.

Read each, integer in turn and calculate its hash value using mod 100 as the hashing function.

Thus, is if the key is <em>k</em>, the hash value h(<em>k</em>) = <em>k </em>mod 100.

When you have finished calculate:

<ol>

 <li>The number of empty entries in the hash table.</li>

 <li>The length of the longest chain.</li>

</ol>

Your program should output these two values – these should be the only outputs.

As usual, do not use classes or STL.