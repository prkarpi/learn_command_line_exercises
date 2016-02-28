> Do this exercise:

```
(master) Nick Vass
Vassio-Book:chapter_14 $ mkdir temp

(master) Nick Vass
Vassio-Book:chapter_14 $ cd temp

(master) Nick Vass
Vassio-Book:temp $ ls
imcool.txt        something.txt     uncool.txt
neat.txt          thefourthfile.txt

(master) Nick Vass
Vassio-Book:temp $ rm uncool.txt

(master) Nick Vass
Vassio-Book:temp $ ls
imcool.txt        neat.txt          something.txt     thefourthfile.txt

(master) Nick Vass
Vassio-Book:temp $ rm imcool.txt neat.txt thefourthfile.txt

(master) Nick Vass
Vassio-Book:temp $ ls
something.txt

(master) Nick Vass
Vassio-Book:temp $ cp -r something.txt chapter_14
```

> Can you remove blah.txt?

Yes, we can remove the file. I ran ```rm blah.txt```


> Let's get rid of our development log file.

not sure of the question.

> Can you remove everything in the slash temp slash foo directory?

it removed the 'foo' directory ```rm -rf temp/foo```
it removed the 'temp' directory ``` rm -rf temp```

> DANGER: Why is it dangerous to run "rm -rf /". DO NOT RUN THIS COMMAND. Simply explain in the Readme.md why it's a very bad idea..

The reason it is dangerous because it is a recursive command; meaning it is will delete everything it finds.
 
 
> 
