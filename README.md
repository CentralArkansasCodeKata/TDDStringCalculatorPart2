TDD String Calculator Part 2 - Interactions
=============

This week we are going to do another TDD Code Kata which will actually build on the previous [TDD String Calculator](http://codekata.co/2013/09/22/tdd-string-calculator/).  So if you didn't do that Code Kata go do that one first and then you can do this one.  According to Roy Osherove this one will take a little more time than the last one.  Just like last time hopefully if you are a TDD expert this will still be fun for you or at least you might learn something new.

###Task
* This builds on the [previous code kata](http://codekata.co/2013/09/22/tdd-string-calculator/).
* It is supposed to be a continuation of learning how to do TDD with unit tests and mocks.
* Don't forget that a good test name will help you stay on track for you test so you don't mock too much and test enough.
* Test name should contain three main parts (according to Roy):
    1. What's being tested
    2. Under what conditions
    3. What should the expected behavior be under those conditions


###Steps
1. Everytime you call Add(string) it also outputs the number result of the calculation in a new line to the terminal or console. (remember to try and do this test first!)
2. Create a program (test first)that uses string calculator, which the user can invoke through the terminal/console by calling **“scalc ‘1,2,3’”** and will output the following line before exiting: **“The result is 6”**
3. Instead of exiting after the first result, the program will ask the user for **“another input please”** and print the result of the new user input out as well, until the user gives no input and just preses enter. in that case it will exit.


###Reference
Thanks to [Roy Osherove's website](http://www.osherove.com) for this [Code Kata](http://osherove.com/tdd-kata-2/).  His website is a good resource to learn how to do TDD and unit tests.  Also his website is a good place to go if this code kata or the previous one from last time is giving you trouble.  He has answers on how to solve them on his website if you need some help.

### Answer Submission Instructions
1. Fork [this github repository](https://github.com/CentralArkansasCodeKata/TDDStringCalculatorPart2).
2. Write your solution to the problem.
3. Commit your solution to the repository.
4. Post a link to your fork as a comment to [this TDD String Calculator Part 2 post](http://codekata.co/2013/10/06/tdd-string-calculator-part-2/) on [codekata.co](http://codekata.co).
