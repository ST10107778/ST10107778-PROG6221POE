# PROG6221POE
 Object-Oriented Programming

# Explanation

The Recipe class defines the data and behaviour related to a single recipe. It has fields to 
store the number, names, quantities, and units of the ingredients, the number and 
descriptions of the steps, and methods to enter, display, scale, reset, and clear the data. The 
Enter Details method asks the user to input the relevant data, which is stored in arrays. The 
Display method prints the recipe in the desired format. The Scale method multiplies all the 
ingredient quantities by a given factor. The Reset method divides all the ingredient 
quantities by 2. The Clear method resets all the data to its initial state.
The Program class contains the main method that creates a Recipe object and displays a 
menu to the user to select what operation to perform. The menu uses a switch statement to 
call the relevant method of the Recipe object based on the user's choice. The program runs 
indefinitely until the user chooses to exit.
The program uses the Console class to interact with the user and the Environment class to 
terminate the program.

# User Interface 
![User Interface](https://user-images.githubusercontent.com/131651299/233941030-01c2aa7b-273a-47a2-9bf9-bcaee0d090ba.PNG)
