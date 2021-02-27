# BrainFck
I wanted to challenge myself by writiing some simple programs in Brainfck. A the language only has 8 operators: 
 - ```+``` adds one to the byte the pointer is at
 - ```-``` subtracts one from the byte the pointer is at
 - ```<``` moves the pointer down one address
 - ```>``` moves the pointer up one address
 - ```.``` output one byte the pointer is at
 - ```,``` input one byte, storing it in the byte at the data pointer
 - ```[``` if the byte at the data pointer is zero, then instead of moving the instruction pointer forward to the next command, jump it forward to the command after the matching ] command.
 - ```]``` if the byte at the data pointer is nonzero, then instead of moving the instruction pointer forward to the next command, jump it back to the command after the matching [ command.
