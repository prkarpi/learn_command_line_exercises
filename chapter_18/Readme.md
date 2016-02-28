# chapter 18 homework

> Do this:

```
(master) Nick Vass
Vassio-Book:chapter_18 $ cat newfile.txt
well, this is my first attempt to write into file using the 'cat' command
line two.
line three.CTRl-d
CTRL-d

cat
exit
:wq
CTRL-d.

(master) Nick Vass
Vassio-Book:chapter_18 $ ls
newfile.txt
```

I could not exit with CTPL-d; I just hit 'control +c'


> Show me the lines in foo.txt that have "ERROR" in them. 

```grep ERROR foo.txt```

> Show me the lines in bar.txt that have "davinci" in them.

```grep davinci bar.txt```

> Can you print all the lines in text files that have your first and last name in them?

I can use quotes to find the first and last names as such:
```grep "first\|last *.*```


> What does -i option does?

It simply ignores the case sensitivity as per using foo or Foo or FOO - becomes one word for 'foo.'
