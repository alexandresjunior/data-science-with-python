# Section #1 - Exercises

1. Define a function called `fullName` which gets the first and last name from the user, using Python's built-in `input` function, stores each name in an individual variable and prints the full name by contatenating the two variables with a space between them.
2. Define a function called `calculateVelocity` which contains two input parameters: `distance` and `time`, calculates the velocity and prints an output similar to `Velocity: 5 m/s`.
3. Define a function `driversLicense` to find out how many years are left before a person can get their driver's license, if they are not of the legal age. Print a message like `You can take the driver's license` in case the user is old enough.
4. Consider a course platform with the following slogan:
    ```
    Technology and Digital Marketing Courses
    ```
    Knowing this, look at the code below with all the words in a list out of order:
    ```
    course_alogan = ['Digital', 'and', 'Marketing', 'Technology', 'Courses']
    ```
    Write a code snippet that displays the slogan in the correct order using Python's indexing features.  
5. Note the following code:
    ```
    a = 2

    if a < 2:
     a = a + 1
    else:
     a = a + 2
    if a < 4:
     a = a - 4
    else:
     a = a + 6

    a
    ```
    What's the value of `a`?
6. To compare the academic performance of a particular student, a school decided to create a graph for each subject, based on the code below:
    ```
    import matplotlib.pyplot as plt

    grades_math = ['Math',8,7,6,6,7,7,8,10]
    grades_english = ['English',9,9,9,8,5,6,8,5]
    grades_geography = ['Geography',10,10,6,7,7,7,8,7]

    grades = [grades_math, grades_english, grades_geography]
    ```
    Generate a graph for each subject using the `grades` list as input and the `matplotlib` library.

**Obs.:** Fork this repository and open a pull request with the exercises solutions.
