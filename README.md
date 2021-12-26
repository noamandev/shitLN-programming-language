# shitLN-programming-language
# 1.0.1 features
To create a shit-ln project

    npm i @puppet-marion/shit-ln
after installing, do the following

    const Terminal = require('shit-ln')

    const my_first_terminal = new Terminal('my_first_terminal')
You can name your terminal anything.
to print a value, type:
 
    my_first_terminal.print('Hello World...') 
  
 to shout a value, type:
 
    my_first_terminal.shout('Hello World!') // this will print "HELLO WORLD!"

To throw an error to the user, type:

    my_first_terminal.Error("You made a mistake! This is an error!")
    
But so far, we are only outputing text to the screen. So let's add some functionaly.
To check the type of a value. ( you need to first print this )

    my_first_terminal.print(my_first_terminal.type("Is this a string?")) // this will output "string"
