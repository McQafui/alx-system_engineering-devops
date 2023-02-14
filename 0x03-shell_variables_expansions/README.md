Shell variables expansions

0. alias ls="rm *"
a script that creates an alias

1. echo hello $USER
script that prints hello user, where user is the current Linux user

2. export PATH=$PATH:/action
script that adds /action to the PATH. /action

3. echo $PATH | tr -s ":" "\n" | wc -l
script that counts the number of directories in the PATH

4. printenv
script that lists environment variables
