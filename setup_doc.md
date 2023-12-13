---
file_format: mystnb
kernelspec:
  name: python3
---
# Setup

## Clone the repository to your local device

Type the ```git clone https://github.com/iperalta7/SparseMatrices-LinkedLists.git``` in the terminal whilst being in the directory that you would like the project to be in

## Creating the executable

Type the ```cd SparseMatrices-LinkedLists``` command to enter the repository directory.

Now that you are in the project directory, type in the ```g++ -std=c++11 main.cpp Matrix.cpp Node.cpp -o run``` command to create the executable for the program

## Executing the executable

Now that we have the executble, we need to execute it. You can use the ```./run small1.txt 3 3 small2.txt 3 3``` to run the program using small 3x3 matrices.

## Providing User Input

The matrices from the files that we provided in the executing command will be shown on the terminal and the program will be asking you what mathematical operation you would like to perform on the matrices shown. 

```
Matrix 1: 
    6    0    2
    0    0    3
    0    2    0
Matrix 2: 
    2    0    0
    1    0    1
    0    1    0
Multiply, Add, Subtract, or Transpose? (M or A or S or T):
```

You have a choice of multiplying, adding, subtracting, and transposing the matrices.

To choose either of those operations, you will need to type in their respective character.

To mulitply, you will need to type ```M```.
To add, you will need to type ```A```.
To subtract, you will need to type ```S```.
To transpose, you will need to type ```T```.

After typing in a character, it will print the resulting matrix on the terminal.

```
Resulting Matrix from Matrix Addition: 
    8    0    2
    1    0    4
    0    3    0
```

If you want to try your own matrix, you can modify matrix files or create your own but you will have to provide the file name in the executing command.
If you want to try our larger matrices, you can change the file names in the executing command to other file names that are provided in our source code.


