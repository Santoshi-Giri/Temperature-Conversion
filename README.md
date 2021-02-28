# Temperature-Conversion

## Summary of the Project
This is a simple C++ program which is written to convert Temperature. It converts temperature from Celsius to Fahrenheit and vice versa.

## Downloading and installing C++:
**1.**	First download Visual C++ 2017 community. It is a free Windows C++ compiler by Microsoft.

**2.**	After that download DEV C ++ 5.11

**3.**	Click on the Source Forge to find the list of download sites and pick one. The file will be something similar to devcpp.4.9.9.2_setup.exe.

**4.**	When the download is completed, click on the “open” button to start the installation process. Then you will see the screen with a pop of message to select language you prefer and ask you to agree the license terms. 

**5.** Carefully follow the instructions and accept the suggested location for installation or else you can change the location and finish the installation.

## Steps for running the program:
**Step 1** : We need to configure Dev C++ in order to modify one of the default settings to allow us to use the debugger with our programs.

**Step 2**:Create a new project. A "project" can simply understood as a particular place where you start to write a code.

**Step 3**:Add or create source files.

**Step 4**:Compile the program which you have written in step 2.

**Step 5**: Execute the program. You can now run your program. 

**Step 6**:Debugging the program which means detecting errors in the program and removing them.

If you face any kind of difficulties while installing ,configuring Dev C++ and debugging then YouTube tutorials will be a great help. If you want advance options for debug then you can simply click on the "Debug" tab at the bottom of the screen.

## Description of the Temperature-Conversion Program
The program first welcome the user and prompt them to select the options to choose their conversion method. It has two options which are Celsius to Fahrenheit or Fahrenheit to Celsius. It takes alphabet "c" or "C" for Celsius and "f" or "F" for Fahrenheit as a option.The program uses if and else if condition to check the options from the user and ask the to enter the number. It takes the number entered by user as an input and place them into the respective formula for conversion. After the calculation has performed, it will display the result. The formula used in the program is given below:

Fahrenheit to Celsius =(input2 - 32) * (5.0/9.0) here, input2 is temperature in Fahrenheit

Celsius to Fahrenheit = (celsius * 9.0) / 5.0 + 32)

![Temperature conversion](https://user-images.githubusercontent.com/79240067/109403805-6fb7cf00-7925-11eb-8b6e-7569dcb2ef16.PNG)


## Uses of each header files, data types, and conditional statements in the program:
**#include -** It is a preprocessor directive which tells the preprocessor to include header files in the program.

**<>**- This sign indicates the start and end of the file name to be included.

**#include iostream**- iostream is a header file which contains functions for input/output operations.

**using namespace std;** std is a namespace for many pieces of functionality which are provided in the standard C++ libraries. 

**int main()** - The main function serves as the starting point of program execution. int denotes that the main()function will return integer value to the system which is after executing the main.

**float** - It is one of the datatype which is used to define numeric values floating decimal points. It can only hold up to 7 significant figures.

**char** - Datatype which stores character data in a fixed length field.

**double** - It is another datatype which define numeric variables holding numbers with decimal points. It can hold 15 to 17 significant digits depending upon the usages.

**cin**- It is an object of the class istream. It is used to accept the input from the standard input device which is keyboard. It may also take input from input streams like files, console etc.

**cout** -It is an object of output stream which is used to show or display output in the screen. 


    if (input1 == 'c')
    {
      cout << "Enter your temperature in Fahrenheit: ";
      cin >> input2;
      cout << endl;
      cout << "Your temperature in Celsius is: " << (input2 - 32) * (5.0/9.0) << endl;
      }  
     else if (input1 == 'F')
     {
    cout << "Enter your temperature in Celsius: ";
    cin >> input2;
    cout << endl;
    cout << "Your temperature in Fahrenheit is: " << (input2 * 1.8) + (32) << endl;
    }

A part of code inserted above shows the use of if and else if statement. These are conditional statement which is used to check the condition and if the condition matches it allows program to perform operation other wise it will throw out error.

**system("pause");**- It is a windows specific command which tells operating software to run the pause program.

**return 0 ;** - It indicates successful execution of program. 




























