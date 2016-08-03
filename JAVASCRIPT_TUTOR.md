## JavaScript Tutor
Visualize code execution to learn Javascript Online

The idea of visualization excites me. As as a learning aid for programming, it even excites me more. The javascript code execution visualize http://www.pythontutor.com/javascript.html#mode=edit is an amazing resource for visualizing your code as it run. You may have a blackbox understanding of what your codes does from its output. But seeing how your code arrives at its justified expectation is the when all the fun begins. That insight if i may a valuable stepping stone to mastery debugging - an indispensable language agnostic skill.  Lets use this resource to go under the hood of a snippet of code in an attempt to solidifying our understanding of pass by value and pass by reference

#### by value
lets declare a variable "a" in javascript and assign it a primitive value

`var a = "a string"`

the variable "a" is pointing to a particular location in memory and lets just call that location 0x100
the primitive "a string" is the the value that sits in that memory location

lets declare another variable "b" and assign it "a" as we have declared previously

`var b = a;`

the variable b is pointing to another particular location in memory and lets call that location 0x200
a copy of the primitive "a string" that "a" points to sits in that memory location

this is happens by default in javascript and is called pass by value
the visualizer better illustrates the mechanism of operation

#### pass by reference
lets create an object

   `var c = {};`

a is pointing to a particular location in memory and let's just call that location (0x300)
the value {} which is an empty object sit there

lets create another variable "d" and assign it "c" as we have created above

`var d = c;`

d points to the same location in memory (0x300)
the value {} which is an empty object sits there
no new copy is created, just two variables pointing to the same memory location and as such changes to one affects the other

this also happens by default in javascript and is called pass by reference


try using the visualizer in live programming mode and see what happens when you change the primitive values
