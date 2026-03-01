# comp304-shell-ish

To run the shelli-ish file:
    rlwrap --always-readline ./shelli-ish
    
This program executes Linux programs such as ls, grep...
To run a command in the bachround append & to the end of the command.

To use >,<,>>,<<, do NOT append a space(e.g., ls>output.txt)

1.cut command:
    Built-in cut command in Linux. It reads lines from input and prints only the specified fields.

2.chatroom command:
    It sets up communication between users in separate terminals.
    Usage: chatroom <roomname> <username>

3.chord command:
    It is a built-in command to find out chord's notes if that chord exists. It calculates and displays spesific notes, intervals and diatonic roles of a triad(chord).
    Usage: chord <RootNote> <Quality>
    Supported Roots(based on music theory): do, do#, re, re#, mi, fa, fa#, sol, sol#, la, la#, si
    Supported Qualities(defaults to maj if quality is not given in the input): maj (or M), min (or m), dim, aug.
    Sample Usage: chord do# min
                  chord fa
                  chord sol dim
