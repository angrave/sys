# Hello Standard Error Stream #
1. Spot the mistake(s) in the following code:
```
  for(len = 0; len <5 ; len++) {
      write(STDOUT_FNO,"I think", 6);
      write(STDOUT_FILENUM,"\n", 6); 
  }
```

2. And use your corrected version in a complete C program to print the following seven lines.
```
I think
I thin
I thi
I th
I t
I
I
```

3. Return the value 7. Verify that your program returns 7 typing `echo $?` in the terminal window after your program has just run.
4. Return the value 1023. Why does `echo $?` in the terminal window after your program has just run not print 1023?
Hint: Some testing or web searching can tell you how many bits are actually used.
