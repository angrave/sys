# Not everything is a system call #
Send standard error to a file `errors.txt` (Hint: 'close' and 'open' are useful).
The file should always be truncated.
Open another file with an illegal filename (e.g. `""`).
Use perror to send the error message to your log file.
Verify the contents of your log file using `cat errors.txt` in the terminal window.
