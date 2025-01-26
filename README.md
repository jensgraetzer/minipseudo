# minipseudo

This is a very small pseudocode programming environment. It may be helpful for beginners who start learning their first programming language.
It is a HTML file, so it runs on most devices, no matter what operating system. Just open the HTML file in a web browser.

You can write the program code, than run it. Here are a few examples:

## Example 1)

    // Calculating the sum of all numbers in an array
    var myArray = [1, 3, 2, 6] 
    print(myArray + "\n") 
    var sum = 0 
    for(var i = 0; i < length(myArray); i++) 
    {  
        sum = sum + myArray[i]  
    }  
    print("The sum all numbers is " + sum  + ".\n") 

## Example 2)

    // Programming an own function
    var a = input("Enter the first number!")
    var b = input("Enter the second number!")
    a = number(a)
    b = number(b)
    var c = addiere(a, b)
    print(c)

    function addiere(nr1, nr2)
    {
        var result = nr1 + nr2
        return result
    }

## Example 3)

    // Two for loops
    for(var i = 0; i < 10; i++) {
        for(var j = 0; j < 10; j++) {
            print(10 * j + i + "   ")  
        }
        print("\n") 
    }

## minipseudo playgrounds

This is a version of the minipseudo programming environment. It contains a playground with 4 by 4 fields.

Use this functions to move a game figure across the field:

* moveForward()
* turnRight()

There are two other functions:

* showGround()
* writeLine()

At the beginning the game figure stands at position [0,0] and looks to the right side.

Use the buttons to see some example code. Run the code to see, what the functions do.

This application is inspired by Swift Playgrounds from Apple.
