Shell variables expansions

0. alias ls="rm *"
creates an alias

1. echo hello $USER
prints hello user, where user is the current Linux user

2. export PATH=$PATH:/action
adds /action to the PATH. /action

3. echo $PATH | tr -s ":" "\n" | wc -l
counts the number of directories in the PATH

4. printenv
lists environment variables

5. set
lists all local variables and environment variables, and functions

6. BEST="School"
creates a new local variable.

7. export BEST="School"
creates a new global variable

8. echo $((128 + $TRUEKNOWLEDGE))
prints the result of the addition of 128 with the value stored in the environment variable TRUEKNOWLEDGE
