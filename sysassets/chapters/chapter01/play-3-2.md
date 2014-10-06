# Writing to files - 2 #
Modify the program so that

* Anyone can read your text file (hint: which mode flag corresponds to "others have read permission"?)
* Rather than truncate the file back to zero length each time, new text is appended to the end.
  For example, running your program twice, and then `cat message.txt` you should see "hello!hello!".
