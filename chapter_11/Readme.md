# chapter 11

> Can you rename foo.txt to blah.txt?

(master) Nick Vass
Vassio-Book:learn_command_line_exercises $ mkdir chapter_11

(master) Nick Vass
Vassio-Book:learn_command_line_exercises $ mine .

(master) Nick Vass
Vassio-Book:learn_command_line_exercises $ cd chapter_11

(master) Nick Vass
Vassio-Book:chapter_11 $ mkdir temp

(master) Nick Vass
Vassio-Book:chapter_11 $ touch foo.txt

(master) Nick Vass
Vassio-Book:chapter_11 $ mv foo.txt temp

(master) Nick Vass
Vassio-Book:chapter_11 $ ls
Readme.md temp

(master) Nick Vass
Vassio-Book:chapter_11 $  cd temp

(master) Nick Vass
Vassio-Book:temp $ ls
foo.txt

(master) Nick Vass
Vassio-Book:temp $ mv foo.txt blah.txt

(master) Nick Vass
Vassio-Book:temp $ ls
blah.txt

> Can you move the production.log file in the log directory to slash temp?

(master) Nick Vass
Vassio-Book:temp $ mkdir log

(master) Nick Vass
Vassio-Book:temp $ cd log

(master) Nick Vass
Vassio-Book:log $ touch production.log

(master) Nick Vass
Vassio-Book:log $ ls
production.log

(master) Nick Vass
Vassio-Book:log $ mv production.log ../temp

(master) Nick Vass
Vassio-Book:log $ ls

(master) Nick Vass
Vassio-Book:log $ cd ..

(master) Nick Vass
Vassio-Book:temp $ cd temp

(master) Nick Vass
Vassio-Book:temp $ ls
production.log

(master) Nick Vass
Vassio-Book:temp $
