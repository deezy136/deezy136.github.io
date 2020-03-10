---
layout: post
title:      "The Importance Of Looping In Ruby"
date:       2020-03-10 04:21:31 -0400
permalink:  the_importance_of_looping_in_ruby
---


In general, looping is the repetitive execution of a piece of code for a given amount of repetitions or until a certain condition is met. Sometimes as a programmer it becomes tedious to keep typing out the same line of code. So the goal is to have our programs behave in a certain way or carry out a certain task with less lines of code. There are a number of different looping methods available for us to accomplish our programming goals. For example if you wanted to print a string ten times. You can type ten print statement, but it is easier to use a loop. The only thing you have to do is to setup a loop to execute the same block of code a specified number of times. One way to accomplish this task is to use the while loop. The while loop executes code repeatedly as long as the condition is true. The following codes prints the string "hello world" 10 times. The condition i < 10 is checked before the loop is entered, then the body executes, then the condition is checked again. When the condition results in false the loop is terminated.
```

i = 0
x = 10

while i < x do

puts "Hello World"

i+=1

end ``
```
The above code shows us that, instead of writing (puts “Hello World’) 10 times, the while loop accomplishes this for us with fewer lines of code. In conclusion, the true importance of looping in ruby, is so that a programmer does not have to repeat  the same line of code a number of times. Instead write efficient, eloquent code with far fewer lines of code.




