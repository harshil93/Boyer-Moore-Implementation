Boyer-Moore-Implementation
==========================

An implementation of Boyer-Moore string matching algorithm to search a pattern in 50 ANSI txt files.

1. The program runs correctly for text files having ONLY ANSI characters. If some other special  
characters, like the additional characters in UTF-8 format are present, it will give erroneous  
results.

2. As specified in project-statement, the code takes input from EXACTLY 50 text files named as  
1.txt, 2.txt, 3.txt.....50.txt (all text files saved in ANSI format).

3. INSTRUCTIONS TO EXECUTE THE CODE...

In the terminal type the following command as per your choice
OPTION#1 ./a.out -np [ If you want to only find the number of occurrences ]
OPTION#2 ./a.out -p [ If you want to print the  occurrences as well ]


Some Post-thoughts!!!
1. The search algorithm implemented (Boyer Moore) is almost universally used in various text-editors for the CTRL+F operation, though with some variants and slight modifications. SO, you can expect our code to work almost as fast as any professional text-editor :)

2. If you wish to print the occurrences in addition to total number of occurrences (equivalent to using -p option with ./a.out), you may feel that running time is too much. Actually, the searching is done almost instantaneously, the output stream is comparatively very slow, causing an apparent delay.