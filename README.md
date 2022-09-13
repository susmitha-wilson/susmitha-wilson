
## Author Details:
Name : Susmitha Wilson
Id   : 110349921

## Project Description:
This project focuses on finding the largest rectangle by area and perimeter among 10 rectangles.

## Language used:
C++
## Code Snippets:
Rectangle.h code
![Rectangle.h file Screenshot](https://olucdenver-my.sharepoint.com/:i:/r/personal/susmitha_wilson_ucdenver_edu/Documents/Recatngle%20Header%20SS.png?csf=1&web=1&e=Tfou13)
Rectangle.cpp code
![Rectangle.cpp file Screenshot](https://olucdenver-my.sharepoint.com/:i:/r/personal/susmitha_wilson_ucdenver_edu/Documents/Recatngle%20SS.png?csf=1&web=1&e=Qyykwc)
Comparator.h code
![Comparator.h file Screenshot](https://olucdenver-my.sharepoint.com/:i:/r/personal/susmitha_wilson_ucdenver_edu/Documents/Comparator%20Header%20SS.png?csf=1&web=1&e=YS8IWX)
Comparator.cpp code
![Comparator.cpp Screenshot](https://olucdenver-my.sharepoint.com/:i:/r/personal/susmitha_wilson_ucdenver_edu/Documents/Comparator%20SS.png?csf=1&web=1&e=sVqZH8)
main.cpp code
![main.cpp Screenshot](https://olucdenver-my.sharepoint.com/:i:/r/personal/susmitha_wilson_ucdenver_edu/Documents/main%20SS.png?csf=1&web=1&e=SgBuEl)

## Structure of the program:
* This C++ program has a Rectangle.h file where the Rectangle class is declared with length and width as private data members and constructors to initialize the objects and get functions to calculate the area and perimeters.
* Definition of the functions in the rectangle class are given in the Rectangle.cpp file
* The Comparator.h file is used to define the function isLessThan which will receive two rectangle objects as argument. It will compare the rectangle objects by perimeter and will return a boolean value. 
* Definition of the functions in the comparator class are given in the Comparator.cpp file
* In main.cpp file findMax template is used to create 10 objects and add them to a vector. Rectangles with random length and width are created using rand() function.
* The created rectangles are displayed
* Comparator object is instantiated and findMax function is used to find the largest rectangle by area and perimeter
* Finally the result is displayed.
* Makefile is created to run the .h and .cpp files
















This will contain the main function as well as findMax template function. It will: 
 
â€¢ It will create ten rectangle objects and add them to a vector. You can either create 
rectangles with random length and width or ask user for the length and width of 
each of the rectangle. 
â€¢ Display a list of all the rectangles (one rectangle per line) 
â€¢ Instantiate an object of comparator class for comparing rectangles by area. Use 
the findMax template function to find the largest rectangle by area and display the 
result. 
â€¢ Instantiate an object of comparator class for comparing rectangles by perimeter. 
Use the findMax template function to find the largest rectangle by perimeter and 
display the result. 
  



## Platform used:
CSE Grid
## Code Compilation Commands:
The Makefile is compiled using make Commands and the output is executed using ./output command.
## Status:
Code runs successfully
## Output:
![Output Screenshot](https://olucdenver-my.sharepoint.com/:i:/r/personal/susmitha_wilson_ucdenver_edu/Documents/Output%20SS.png?csf=1&web=1&e=Elo9oG)
