# Milestone 1: Fahrenheit to Celsius Converter
This program will enable the user to input temperature in Fahrenheit then convert it to Celsius. It will also provide some comments depending on the converted temperature.

# How to run it.
Click the play button. Enter the numeric value of the temperature in Fahrenheit when prompted. The end user will be given 5 attempts to come up with the correct input; otherwise, the code will terminate automatically. Once a valid input is provided, the program displays the converted temperature in Celsius.

# Challenges that I debugged.
As a newbie in Python, I learned the importance of adding colons (:) at the end of the function definitions and if-elif-else conditional statements. 

Locating where to type the value as required by the 'input() was also a bit tricky. I tested my code via Google Colab and a standard Python script (.py) to confirm that works correctly. The input box appears directly at the bottom of the code cell in Google Colab, whereas, it appears at the bottom inside the Terminal View in Python (.py) script. Apparently, in Jupyter Notebooks, the input box appears at the upper middle portion of the screen.

I also had to anticipate unexpected user inputs, such as entering alphabetical text instead of numbers. This led me to implement while loop and try and except to address the Value Error. Ultimately, I had to figure out how to stop the loop cleanly without throwing another exception. 
