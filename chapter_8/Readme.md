#chapter 8

> Explain the 'pushd' and 'popd' in your own words.

  The 'pushd' command temporarily "stashes" your current directory for later use while changes you to another directory; similarly, 'popd' takes your "stashed" directory and switches you over to it.
  
  
> Do more exercises

  (master) Nick Vass
  Vassio-Book:learn_command_line_exercises $ pushd chapter_2
  ~/workspace/davinci_coders_t1_2016/homework/learn_command_line_exercises/chapter_2 ~/workspace/davinci_coders_t1_2016/homework/learn_command_line_exercises
  
  (master) Nick Vass
  Vassio-Book:chapter_2 $ popd
  ~/workspace/davinci_coders_t1_2016/homework/learn_command_line_exercises
  
  (master) Nick Vass
  Vassio-Book:learn_command_line_exercises $ pushd ../../../../
  ~ ~/workspace/davinci_coders_t1_2016/homework/learn_command_line_exercises
  
  
  Vassio-Book:~ $ pwd
  /Users/user
  
  
  Vassio-Book:~ $ popd
  ~/workspace/davinci_coders_t1_2016/homework/learn_command_line_exercises
  
  (master) Nick Vass
  Vassio-Book:learn_command_line_exercises $
  
  Vassio-Book:/ $ cd tmp
  
  
  Vassio-Book:tmp $ popd
  ~/workspace/davinci_coders_t1_2016/homework/learn_command_line_exercises
  
  (master) Nick Vass
  Vassio-Book:learn_command_line_exercises $

