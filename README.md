# Temperature-Conversion

## Summary of Project
This is a simple C++ program which is written to convert Temperature. It converts temperature from Celsius to Fahrenheit and vice versa.

## Downloading and installing c++:
**1.**	First download Visual c++ 2017 community. It is a free Windows C++ compiler by Microsoft.
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

If you face any kind of difficulties while installing ,configuring Dev C++ and debugging then Youtube tutorials will be a great help.If you want advance options for debug then you can simply click on the "Debug" tab at the bottom of the screen.

## Description of the Temperature-Conversion Program:
The program first welcome the user and prompt them to select the options to choose their conversion method. It has two options which are Celsius to Fahrenheit or Fahrenheit to Celsius. It takes alphabet "c" or "C" for celsius and "f" or "F" for fahrenheit as a option.The program uses if and else if condition to check the options from the user and ask the to enter the number. It takes the number entered by user as an input and place them into the repective formula for conversion. After the calculation has performed, it will display the result. The formula used in the program is given below:

Fahrenheit to Celsius =(input2 - 32) * (5.0/9.0) here, input2 is temperature in Fahrenheit

Celsius to Fahrenheit = (celsius * 9.0) / 5.0 + 32)

## Uses of each header files,data types, and conditional statements in the program:
**#include -** It is a preprocessor directive which tells the preprocessor to include header files in the program.

**<>**- This sign indicates the start and end of the file name to be included.

**#include iostream**- iostream is a header file which contains functions for input/output operations.

**using namespace std;** std is a namespace for many pieces of functionality which are provided in the standard C++ libraries. 

**int main()** - The main function serves as the starting point of program execution. int denotes that the main()function will return integer value to the system which is after executing the main.

**float** - It is one of the datatype which is used to define numeric values floating decimal points. It can only hold upto 7 significant figures.

**char** - Datatype which stores character data in a fixed length field.

**double** - It is another datatype which define numeric variables holding numbers with decimal points.It can hold 15 to 17 significant digits depending upon the usages.

**cin**- It is an object of the class istream. It is used to accept the input from the standard input device which is keyboard.It may also take input from input streams like files,console etc.

**cout** -It is an object of output stream which is used to show or display output in the screen. 

![](https://github.com/Santoshi-Giri/Temperature-Conversion/blob/main/Capture1.PNG)

 ** if (input1 == 'c')**
    {
      cout << "Enter your temperature in Fahrenheit: ";
      cin >> input2;
      cout << endl;
      cout << "Your temperature in Celsius is: " << (input2 - 32) * (5.0/9.0) << endl;
    }

    else if (input1 == 'C')
    {
      cout << "Enter your temperature in Fahrenheit: ";
      cin >> input2;
      cout << endl;
      cout << "Your temperature in Celsius is: " << (input2 - 32) * (5.0/9.0) << endl;
    }

    if (input1 == 'f')
  {
    cout << "Enter your temperature in Celsius: ";
    cin >> celsius;
    fahrenheit = (celsius * 9.0) / 5.0 + 32;
    cout << "Your temperature in Fahrenheit is: " << fahrenheit << endl;
    
  }

  else if (input1 == 'F')
  {
    cout << "Enter your temperature in Celsius: ";
    cin >> input2;
    cout << endl;
    cout << "Your temperature in Fahrenheit is: " << (input2 * 1.8) + (32) << endl;
  }















