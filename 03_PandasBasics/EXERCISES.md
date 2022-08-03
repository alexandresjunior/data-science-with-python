# Section #3 - Exercises

1. Consider the dictionary below:
    ```
    {'Crossfox': {'km': 35000, 'year': 2005, 'km_avg': 2500.0},
    'DS5': {'km': 17000, 'year': 2015, 'km_avg': 4250.0},
    'Fusca': {'km': 130000, 'year': 1979, 'km_avg': 3250.0},
    'Jetta': {'km': 56000, 'year': 2011, 'km_avg': 7000.0},
    'Passat': {'km': 62000, 'year': 1999, 'km_avg': 3100.0}}
    ```
    Write a code snippet which results in the following `DataFrame`:
    |          |    km    |  year  |  km_avg  |
    |:--------:|:--------:|:------:|:--------:|
    | Crossfox | 35000.0  | 2005.0 | 2500.0   |
    | DS5      | 17000.0  | 2015.0 | 4250.0   |
    | Fusca    | 130000.0 | 1979.0 | 3250.0   |
    | Jetta    | 56000.0  | 2011.0 | 7000.0   |
    | Passat   | 62000.0  | 1999.0 | 3100.0   |

    **Tip**: `ndarray.T`: Returns the transposed array, i.e. converts rows to columns and vice versa.
2. Consider the following code:
    ```
    import pandas as pd

    data = {
        'Name': ['Jetta', 'Passat', 'Crossfox', 'DS5', 'Beetle'],
        'Engine': ['4.0 Turbo Engine', 'Diesel Engine', 'V8 Diesel Engine', '2.0 Engine', 1.6 Engine'],
        'Year': [2019, 2003, 1991, 2019, 1990],
        'Mileage': [0.0, 5712.0, 37123.0, 0.0, 120000.0],
        'Zero_km': [True, False, False, True, False],
        'Value': [88000.0, 106000.0, 72000.0, 89000.0, 32000.0]
    }

    dataset = pd.DataFrame(data)
    ```
    Write a code snippet which selects only the `Name`, `Year`, `Mileage` and `Value` information of `Passat` and `Crossfox` cars.
3. Consider the following code:
    ```
    import pandas as pd

    data = {
        'Engine': ['4.0 Turbo Engine', 'Diesel Engine', 'V8 Diesel Engine', '2.0 Engine', 1.6 Engine'],
        'Year': [2019, 2003, 1991, 2019, 1990],
        'Mileage': [0.0, 5712.0, 37123.0, 0.0, 120000.0],
        'Zero_km': [True, False, False, True, False],
        'Value': [88000.0, 106000.0, 72000.0, 89000.0, 32000.0]
    }

    dataset = pd.DataFrame(data, index = ['Jetta', 'Passat', 'Crossfox', 'DS5', 'Beetle'])
    ```
    Write code snippets which result in the following `DataFrame` using *.loc* and *.iloc* functions:
    |        |     Engine     |   Value  |
    |:------:|:--------------:|:--------:|
    | Passat | Diesel Engine  | 106000.0 |
    | DS5    | Engine 2.0     | 89000.0  |
4. Use the following `DataFrame` to answer the question:
    ```
    import pandas as pd

    data = {
        'Engine': ['4.0 Turbo Engine', 'Diesel Engine', 'V8 Diesel Engine', 'Diesel Engine', '1.6 Engine'],
        'Year': [2019, 2003, 1991, 2019, 1990],
        'Mileage': [0.0, 5712.0, 37123.0, 0.0, 120000.0],
        'Zero_km': [True, False, False, True, False],
        'Value': [88000.0, 106000.0, 72000.0, 89000.0, 32000.0]
    }

    dataset = pd.DataFrame(data, index = ['Jetta', 'Passat', 'Crossfox', 'DS5', 'Beetle'])
    ```
    Write a code snippet which returns the `DataFrame` below.
    |        |      Engine      | Year | Mileage | Zero_km |   Value  |
    |:------:|:----------------:|:----:|:-------:|:-------:|:--------:|
    | Jetta  | Turbo Engine 4.0 | 2019 | 0.0     | True    | 88000.0  |
    | Passat | Diesel Engine    | 2003 | 5712.0  | False   | 106000.0 |
    | DS5    | Diesel Engine    | 2019 | 0.0     | True    | 89000.0  |

**Obs.:** Fork this repository and open a pull request with the exercises solutions.