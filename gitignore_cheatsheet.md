pattern | explanation | examples
   -------------------------
 logs   | directories and files named logs will be ignored | /log/debug.log, build/logs   
/debug.log | prepending slash matches files only in the repository root| debug.log
logs/ | the entire contents of any directory in the repository matching the name will be ignored| logs/latest/foo.bar
*txt| ignore all .txt files | scool.txt
# | lines starting with # are ignored | #ignore this line
