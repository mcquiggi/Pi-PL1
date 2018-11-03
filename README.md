# Pi-PL1
Compute Pi to an arbitrary number of digits using IBM's old PL/I language.  Why, you ask? Why not?

The program uses Machin's series for computation of pi. See https://en.wikipedia.org/wiki/John_Machin for details.

This is a copy of the card deck (?!) used to compile and link the program under MVS 3.7j, an old IBM mainframe OS for the System/360 and System/370 circa 1975-1980.  It was leading-edge, state-of-the-art for its era.

JCL (Job Control Language) statements for compiling, linking, and running the program are included.

If you're not familiar with this ancient technology, there are resources online.  Check out the "Hercules" IBM emulator, but be prepared for significant differences in concept.  Your understanding of computing, OSes, build processes, user interfaces, etc will be challenged.  It's not "better", or "worse", it's just different!

The number of digits to compute is specified in the input data read near the end of the file after the

```
//GO.SYSIN DD *
```

statement.

To compile/link/run, just submit the job to your handy MVS job queue.  I use HASP.  You can figure it out!

This is standard PL/I circa 1980.

There is a FORTRAN port of this code in my GitHub account as well.  Have fun!

K. McQuiggin
