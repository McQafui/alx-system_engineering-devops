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

9. echo $((POWER/DIVIDE)) 
displays the result of BREATH to the power LOVE

10. echo $((BREATH**LOVE))
displays the result of BREATH to the power LOVE

11. echo $((2#${BINARY}))
converts a number from base 2 to base 10.

12. printf "%s\n" {a..z}{a..z} | grep -v "oo"
prints all possible combinations of two letters, except oo

13. printf "%.2f\n" "$NUM"
prints a number with two decimal places, followed by a new line.

14. printf "%x\n" "$DECIMAL"
converts a number from base 10 to base 16

15. cat | tr 'A-Za-z' 'N-ZA-Mn-za-m'
encodes and decodes text using the rot13 encryption. Assume ASCII

16. cat -n | grep [13579][[:space:]] | tr -s ' ' | cut -f2
prints every other line from the input, starting with the first line

17. printf '%o\n' $(( 5#$( echo $WATER | tr water 01234) + 5#$( echo $STIR | tr stir. 01234 ) )) | tr 01234567 bestchol
adds the two numbers stored in the environment variables WATER and STIR and prints the result
