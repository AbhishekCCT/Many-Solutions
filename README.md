# Many-Solutions
For each problem, lets compile 'the best Ideas' and 'the best Solutions'.

So I was solving a problem (at edX-MIT6.00.1x) and it began there...

-The problem was to find the number of times 'bob' occurs in a given string. 

As I started to work out a solution, I quickly found one.  I can iterate over the characters in the string, where I find a 'b', I'll check for the next two characters if they were 'o' and 'b' (making it whole as 'bob').

I wrote down the code and after a few silly mistakes, I finalised this as my solution:

##Code with i+1 and i+2 


And after writing this I realised, "Oh!!!, I could have sliced the strings and it would be more pythonic also(my first language was C++)". So I came up with a slight improvement over it :

#Code with slicing...



And that's when it dawned upon me, what if the string was not 'bob', what if the size of the string not equal to the one I have used! What if the next question is about 'hariom' or 'sumit' or...or...or...'Special'?

-The answer was, I'll have to go back and change the code so that it works for the given substring. I thought it would be a bad practise to go to the source file and make changes. 

So, I came up with this...

#Code with better reusability...


Then it came to me that I won't always be the one with the best of the ideas or solutions(I'm sure this can be done in a far better way then it is now). So I've created this repo to make a bank of "best of the ideas" and the "best of the solutions" in a "many-solution" way.

What do we mean by...
-best of the ideas: What we want here is a more general solutions, which are applicable to all possible input and output scenarios (if possible include test cases also).
-best of the solutions: Along with being really good idea, if it is more efficient, makes it a better solutions. While coming up with better solutions, we'll always end up with best of the solutions!

Lets make it happen!!!
