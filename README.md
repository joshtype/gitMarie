MARIE (Machine Architecture that's Really Intuitive and Easy) is a simulation of a
machine architecture and assembly language. It was created using Java and Java Swing by
Linda Null and Julia Lobur and published in "The Essentials of Computer Organization and
Architecture". A web-based version written in JavaScript, written by Jason Nguyen, 
Saurabh Joshi, Eric Jiang, and Erfan Norozi is available at https://marie.js.org/.

It is used in educational settings to help students understand how computers are 
organized and how assembly instructions impact registers and memory. The format for 
assembly instructions is: [<label>,] operator [operand] [/<comment>]. Each line must end 
with a carriage-return by pressing [ENTER] to move to the next line. There are are small 
number of instructions that can be entered. This makes MARIE assembly programs easy to 
learn but can quickly grow complex for operations that are quite simple for high level 
languages.

The version used for this repository was edited by Professor Neal Rogers of Columbus
State University in Columbus, GA.
  Changes:
    SUBT instruction is changed to SUB. 
    DSA (Define Symbolic Address) is added. 
    A label is required for END directives.
    JnS and HALT opcodes are swiched (JnS opcode 7, Halt opcode 0).
    Added LoadI (Load Indirect) command.
    Added AddM  (Add Immediate) command.
    Added SubM  (Subtract Immediate) command.
    All occurrences of show() changed to setVisibility(true).

Credit:
Null, Linda and Lobur, Julia. "The Essentials of Computer Organization and Architecture".
Jones & Bartlett Publishers, 2014.
https://books.google.com.au/books?id=3kQoAwAAQBAJ.
