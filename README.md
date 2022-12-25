
## Password Rules
Passwords may only be six digits, i.e. there are no alphabetical or special
characters. 

The final lock is a string of three two-digit numbers. The lock operates y entering a number clockwise, then counterclockwise, and finally clockwise. 
For example, 031415 corresponds to a lock pattern of clockwise until 3, counter-clockwise until 14, and clockwise until 15.

The bleach executable expects a single command line argument, i.e. './bleach 1', or './bleach 031415'. When the password is found, the executable will output "Accepted!" to stdout.

It should only take you a minute and a half to brute force from the worst case, though you may use any methods you wish. You will not be judged on code quality for this assignment.


