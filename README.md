# minipseudo
This is a very small pseudocode programming environment. It may be helpful for beginners who start learning their first programming language.
It is a HTML file, so it can be executed on every operating system. Just open the file in a Webbrowser.

You can write program code and run it afterwards. Heare are some examples.

## Example 1)

    // Calculating the sum of all numbers in the array
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

    // Two for-Loops
    for(var i = 0; i < 10; i++) {
        for(var j = 0; j < 10; j++) {
            print(10 * j + i + "   ")  
        }
        print("\n") 
    }
