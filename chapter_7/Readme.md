#Chapter_7

> Can you remove the tmp directory?

(mistakenly I created tmp/stuff ... and so on in learn_command_line_exercises not inside the chapter_7 directory); I tried to remove:

Vassio-Book:learn_command_line_exercises $ rmdir tmp
rmdir: tmp: Directory not empty

Apparently if the directory is not empty it cannot be removed. I will remove each directory that's inside the temp and then try to remove the temp itself. Ley us see what would happen:
 
 Vassio-Book:learn_command_line_exercises $ cd tmp/stuff/things/frank/joe/alex/john
 
 (master) Nick Vass
 Vassio-Book:john $ pwd
 /Users/user/workspace/davinci_coders_t1_2016/homework/learn_command_line_exercises/tmp/stuff/things/frank/joe/alex/john
 
 (master) Nick Vass
 Vassio-Book:john $ cd ..
 
 (master) Nick Vass
 Vassio-Book:alex $ rmdir john
 
 (master) Nick Vass
 Vassio-Book:alex $ ls
 
 (master) Nick Vass
 Vassio-Book:tmp $ cd ..
 
 (master) Nick Vass
 Vassio-Book:learn_command_line_exercises $ rmdir tmp 
 
 I removed the temp directory.
 
 
