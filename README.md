Exercise 1 -
-Please use advanced scripting language (Python)
-Please implement a stand-alone script that does the following function:

Input: 
taking an argument “root_dir” as a root directory to start traversing 
taking an argument “keyword” as a regular expression for example ( “^[a-zA-Z]+_TESTResult.*” ) to detect a file contains an interested string

Functionality:
script should recursively walk the “root_dir” and detect all the files under that dir contains “keywords” and count the number of files for that sub dir. All results should be saved in a key:value array with key being subdir string, and value being counts of file contains the key line 

Output:
A output array of all the data, for example {’a/b’: 6, ’a/b/c’: 7, ‘/a/b/c/d’:0}
An output graph with a plot with X as subdir name string, Y as count values. 

Tests:
Please design a set of tests for the above routine you just wrote, how many ways can break the routine above and how many ways can you test the routine

