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
* Python is a popular [open-source](https://pt.wikipedia.org/wiki/Software_de_c%C3%B3digo_aberto) programming language. This means that Python is developed under an [OSI](https://pt.wikipedia.org/wiki/Open_Source_Initiative)-approved open-source license, making it freely usable and distributable, even for commercial use. The Python license is administered by the [Python Software Foundation](https://pt.wikipedia.org/wiki/Python_Software_Foundation).

## Sections
1. [Programming Logic with Python](./01_ProgrammingLogicWithPython/)
2. [Numpy Basics](./02_NumpyBasics/)

## Additional Links
* [What is Google Colaboratory?](https://www.alura.com.br/artigos/google-colab-o-que-e-e-como-usar?utm_source=gnarus&utm_medium=timeline)
* [Python and Object Orientation](https://www.alura.com.br/apostila-python-orientacao-a-objetos#entrada-do-usurio)
* [Why Can't Computers Generate Random Numbers?](https://www.youtube.com/watch?v=LqXnpIn2Uxs)
