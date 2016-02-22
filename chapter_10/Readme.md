# chapter 10

> Can you copy the foo.txt file into the tmp directory?

I created a new file in terminal using 'touch' command; created a new 'tmp' directory; then I copied like so:

(master) Nick Vass
Vassio-Book:chapter_10 $ cp foo.txt tmp/

(master) Nick Vass
Vassio-Book:chapter_10 $ ls
foo.txt    footwo.txt tmp

(master) Nick Vass
Vassio-Book:chapter_10 $ cd tmp

(master) Nick Vass
Vassio-Book:tmp $ ls
foo.txt

(master) Nick Vass
Vassio-Book:tmp $


> Can you copy .bash_profile in your home directory to the current directory?

I could not find the file .bash_profile file.

> Use 'cp -r' to copy a directory.

(master) Nick Vass
Vassio-Book:chapter_10 $ cp -r tmp tmp_two

(master) Nick Vass
Vassio-Book:chapter_10 $ ls
Readme.md  foo.txt    footwo.txt tmp        tmp_two

(master) Nick Vass
Vassio-Book:chapter_10 $ cd tmp_two

(master) Nick Vass
Vassio-Book:tmp_two $ ls
tmp

(master) Nick Vass
Vassio-Book:tmp_two $

> Copy a file to your home directory.

(master) Nick Vass
Vassio-Book:chapter_10 $ cp foo.txt ~/

(master) Nick Vass
Vassio-Book:chapter_10 $ cd ~/


Vassio-Book:~ $ ls
Applications     Downloads        Pictures         foo.txt
BitTorrent Sync  Library          Public           workspace
Desktop          Movies           RubymineProjects
Documents        Music            Sites


Vassio-Book:~ $
