# Pattern-Search
Program that recursively walks a root dir to find a pattern specified from command line

Requirements:

A stand-alone script that does the following function:

Input: 
taking an argument “root_dir” as a root directory to start traversing 
taking an argument “keyword” as a regular expression for example ( “^[a-zA-Z]+_TESTResult.*” ) to detect a file contains an interested string

Functionality:
script should recursively walk the “root_dir” and detect all the files under that dir which contains “keywords” and count the number of files for each sub dir. All results should be saved in a key:value array with key being subdir string, and value being counts of files containing the keyword 

Output:
An output array of all the data, for example {’a/b’: 6, ’a/b/c’: 7, ‘/a/b/c/d’:0}
