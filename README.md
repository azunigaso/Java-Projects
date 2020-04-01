# Java-Projects
A collection of projects ranging from data structures, games, and simple applications using JAVA. 

# Style Checker
The provided cs310code.xml checks for common coding convention mistakes (such as indentation and naming issues). 
You can use the following to check your style:
```
java -jar checkstyle.jar -c [style.xml file] [userDirectory]/*.java
```
For example, for a user directory 001-krusselc-p0 checking for JavaDoc mistakes I would use:
```
java -jar checkstyle.jar -c cs310code.xml 001-krusselc-p0/  *.java
```
Note:
if you have a lot of messages from checkstyle, you can add the following to the end of the command to output it to a file called out.txt: > out.txt
 
If checkstyle finds nothing wrong you’ll see “Starting audit... Audit done.” and nothing else.

# JavaDoc Checker
Checking Your JavaDoc CommentsYou should
verify that your JavaDoc comments adhere to the proper format (especially if you’re new to writing JavaDocs). We’ve provided a second checkstyle file (cs310comments.xml) that looks for JavaDoc issues and in-line comment indentation issues. You can run it the same way as cs310code.xml, for example: 
```
java -jar checkstyle.jar -c cs310comments.xml 001-krusselc-p0/  *.java
```
