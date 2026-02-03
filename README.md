Version 0.81 (beta)

This is a work in progress release of Rogue.  The text graphics
game from the early 1980s.  I have done my best to port it over
and continue to make refinements, but wanted to share to get
feedback on the implementation and overall feel.

The game is very long to play and does not currently
support saving or high scores yet.  That's in the works.  What
this really means is that you will probably not complete the game
in its current form.  That's not to say you won't have fun.  I
am just trying to let you know there's a very slim chance you will
make it to the end of the game since I don't have save implemented
yet.

So here we go...

**Welcome to Rogue for the TI-84 Plus CE!**

Welcome to Rogue!  The 1980s era game that I have managed to
compile and get running on a TI-84 Plus CE with a very stripped-down
Unix "curses" implementation I wrote. It uses an 8x8 font to yield a
40x30 screen display.

First things first:  This game requires you to have a TI-84 Plus
CE that has been "educated" to run C and assembly language
programs.  If you don't have this or don't know what it means.
You have a quest to complete before you can play this game. :-)

Second: You do need to know how to exit the game.  You must press
"Clear" and then "Enter".  If you see a prompt for "--More--" at
the top of the screen, the game expects you to press "y=".  You
are not able to exit if the "--More--" is displayed until you clear
it with "y=".  It is on you if your teacher, professor, significant
other, or other being who does not approve of your playing games
on your calculator catches you before you exit.

Third: Read the accompanying rogue.doc.txt or rogue.html files
to provide the backstory and also to learn how to play the game.
Doing so will save you a lot of frustration later.

Finally:  Here's a key mapping of the keys during gameplay to
their "keyboard" equivalents per the rogue instructions mentioned
above:

Pressing and holding a key will cause it to repeat just like a
computer keyboard would.

All alpha keys (A-Z) return their lower-case equivalent character for
program control.  Alpha acts as a shift key for the alpha keys to
enable entry of capital letters.  For example:  To take off your
current armor you would hold Alpha while pressing T.  Please note
that calculator emulators will fall short in their ability to
fully play the game due to the large number of commands in Rogue
and the use of upper-case characters for commands.  This may be
addressed in future versions, but for the moment the focus is
to run on the calculator.

Key mappings for convenience are as follows:
```
Direction pad maps to direction keys. Including diagonals.
y= maps to space for stepping through prompts quickly.
Window maps to 's' for quick searching for traps and hidden doors/passages.
Zoom maps to ^ for identifying trap types
Graph maps to i for quick inventory access
2nd maps to *
Mode maps to ESC
Del maps to < in order to climb a staircase
Stat maps to > in order to descend a staircase
Clear maps to Q for quitting the program
Vars maps to . to cause the player to rest one turn
Enter maps to carriage return.
```

Differences from the original game:
```
? Help screen is not supported.  It's just too big.
/ The identify command is not supported
h, H, ^H commands are not supported
o command is not supported
, Pick something up that is under you
! Escape to shell has nowhere to go
S Not currently supported
) Use inventory to see what you are using
] Use inventory to see what you are wearing
= Use inventory to see what rings you are wearing@ We have a dedicated area for this line so this isn't needed
```

A note on bug reporting:
I will monitor Github for bug reports.  Please review
existing bug reports before reporting new issues.

One thing I know will be reported if I don't mention it is the
situation where all items on the screen keep shifting in type with
the exception of the staircase.  This is not a bug.  You drank
a potion that is equivalent to LSD and you are tripping.  All I
can say is deal with it.  If you have a lot of food, hunker down
in a corner of a room and press "vars" until the effect wears off.
Otherwise, you need to continue to trip out while you fight your
way through the dungeon so you don't starve to death.

Happy dungeon crawling...


**Credit where credit is due**

The original work for this game was performed by Michael C. Toy and
Kenneth C. R. C. Arnold at UC Berkeley in California.  Readers are
directed to rogue.doc.tx and specifically the Acknowledgements
sections of that document for a full list of those responsible for
the original game.

This project would also not be possible without the archival efforts
of David Silva (see https://github.com/Davidslv).  I was just
ecstatic when I came across this archive and the fact that David
Silva had preserved it in its original form.

