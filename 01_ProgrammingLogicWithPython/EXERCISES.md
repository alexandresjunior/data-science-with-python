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
7. Consider the variables below:
    ```
    text = 'The vehicle's average mileage is '
    km = 100000
    year_current = 2019
    year_manufacture = 1999
    ```
    Write a code snippet whose output is: `The vehicle's average mileage is 5000 km` using those variables as inputs.
8. Consider the `cars` list below:
    ```
    cars = [
         [
             'Jetta Variant',
             '4.0 Turbo Engine',
             2003,
             False,
             ['Alloy wheels', 'Power locks', 'Autopilot']
         ],
         [
             'Passat',
             'Diesel engine',
             1991,
             True,
             ['Multimedia centre', 'Panoramic roof', 'ABS brakes']
         ]
    ]
    ```
    Write a code snippet whose outputs are: `True`, `'Panoramic roof'` and `['Alloy wheels', 'Power locks', 'Autopilot']`.
9.  Consider the following Python list:
    ```
    accessories = [
         'Alloy wheels',
         'Electric Locks',
         'Automatic pilot',
         'Leather Seats',
         'Air conditioning'
    ]
    ```
    Write a code snippet whose output obtained after a set of manipulations is:
    ```
    ['Air bag',
     'Air conditioning',
     'Leather Seats',
     'Automatic pilot',
     'Alloy wheels',
     'Electric windows']
    ```
10. Consider the following code snippet:
    ```
    square = []
    for i in range(10):
       square.append(i ** 2)
    ```
    Write a code snippet whose output is the same using *list comprehensions*.
11. Consider the following tuple:
    ```
    cars = (
        (
            'Jetta Variant',
            '4.0 Turbo Engine',
            2003,
            False,
            ('Alloy wheels', 'Power locks', 'Autopilot')
        ),
        (
            'Passat',
            'Diesel engine',
            1991,
            True,
            ('Multimedia centre', 'Panoramic roof', 'ABS brakes')
        )
    )
    ```
    What are the output for `carros[0][3]`, `carros[-1][-1][-1]` and `carros[0][-1][:2]`?
12. For the same tuple above, write a code snippet whose output is as below:
    ```
    Alloy wheels
    Electric locks
    Automatic pilot
    Multimedia center
    Panoramic roof
    ABS brakes
    ```
13. Consider the two lists below:
    ```
    names = ['Passat', 'Crossfox', 'DS5', 'C4', 'Jetta']
    kms = [15000, 12000, 32000, 8000, 50000]
    ```
    Write a code snippet which makes it possible to print the names of vehicles with mileage below 20,000 km.
14. Consider the following dictionary:
    ```
    data = {
        'Passat': {
            'year': 2012,
            'km': 50000,
            'value': 75000,
            'accessories': ['Airbag', 'ABS']
        },
        'Cross Fox': {
            'year': 2015,
            'km': 35000,
            'value': 25000
        }
    }
    ```
    Write code snippets to make it possible to:
    1. Test if the `accessories` key exists in the `Crossfox` car information dictionary (Answer: `False`)
    2. Test if the `accessories` key exists in the `Passat` car information dictionary (Answer: `True`)
    3. Get the `Crossfox` car value (Answer: `25000`)
    4. Access the latest `Passat` car accessory (Answer: `'ABS'`)
15. Consider the following dictionary:
    ```
    data = {
        'Crossfox': {'value': 72000, 'year': 2005},
        'DS5': {'value': 125000, 'year': 2015},
        'Beetle': {'value': 150000, 'year': 1976},
        'Jetta': {'value': 88000, 'year': 2010},
        'Passat': {'value': 106000, 'year': 1998}
    }
    ```
    Write a code snippet which displays the code that prints only the **names of vehicles** with a year of manufacture greater than or equal to 2000.

**Obs.:** Fork this repository and open a pull request with the exercises solutions.
