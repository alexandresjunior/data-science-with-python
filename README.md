# Data Science with Python
First steps in Python programming language with a focus on Data Science

## Environment Setup
* To take this course, it is not necessary to download any program or software. We are going to use a tool from Google called [Google Collaboratory](https://colab.research.google.com/notebooks/welcome.ipynb#scrollTo=FQ_Hx_9tn7uF) (aka **Colab**).
* To use this tool, you must have a Google account, as all code will be stored in Google Drive.

## About Python
* Python is a **high-level programming language**, which means they are more like human languages, whereas low-level languages are more similar to machine structures, as the **Assembly** code example below.

```
section.text align=0

global _start

message db 'Hello, world!', 0x0a

len equ $ - messagem

_start:
    mov eax, 4 ;SYS_write
    mov ebx, 1 ;Number of file descriptor (1=stdout)
    mov ecx, message ;Pointer to the string.
    mov edx, len ;message size
    int 0x80

    mov eax,1
    int 0x80
```
* This code is for displaying the **Hello, world!** message. In Python we write:
```
print("Hello, world!")
```
* Although it is more difficult for the human developer to understand, the low-level language generates better use and performance of the machine, after all the content does not need to be interpreted by the computer, unlike high-level languages.

## Additional Links
* [What is Google Colaboratory?](https://www.alura.com.br/artigos/google-colab-o-que-e-e-como-usar?utm_source=gnarus&utm_medium=timeline)
* [Python and Object Orientation](https://www.alura.com.br/apostila-python-orientacao-a-objetos#entrada-do-usurio)

## Exercises
1. Define a function called `fullName` which gets the first and last name from the user, using Python's built-in `input` function, stores each name in an individual variable and prints the full name by contatenating the two variables with a space between them.
2. Define a function called `calculateVelocity` which contains two input parameters: `distance` and `time`, calculates the velocity and prints an output similar to `Velocity: 5 m/s`.
3. Define a function `driversLicense` to find out how many years are left before a person can get their driver's license, if they are not of the legal age. Print a message like `You can take the driver's license` in case the user is old enough.
