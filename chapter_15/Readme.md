#chapter 15 homework

> Can you put "This class is fun" into bar.txt?

```
(master) Nick Vass
Vassio-Book:chapter_15 $ echo "This class is fun" > bar.txt

(master) Nick Vass
Vassio-Book:chapter_15 $ cat bar.txt
This class is fun
```

> Can you put "Oh so much fun" into foo.txt?

```
(master) Nick Vass
Vassio-Book:chapter_15 $ echo "Oh so much fun" > foo.txt

(master) Nick Vass
Vassio-Book:chapter_15 $ cat foo.txt
Oh so much fun
```

> Explain the | > < >> commands.

The '|' takes the output from the command on the left and transfers it to the command on the right.
The '<' takes the input from the right file and transfers it to the left program.
The '>'takes the output of the command on the left and writes it to the fie on the right.
The '>>' takes the output of the command on the left and appends it ot the file on the right.


