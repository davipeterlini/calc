# Simple Calculator

This is a simple calculator module in Python that supports basic arithmetic operations such as addition, subtraction, multiplication, and division.

## Setup

1. Clone the repository:
    ```sh
    git clone <repository-url>
    cd <repository-directory>
    ```

2. Ensure you have Python installed. You can download it from [python.org](https://www.python.org/).

## Usage

You can run the calculator module directly to see some example operations:

```sh
python calculator.py
```

This will output:

```
Addition: 2 + 3 = 5
Subtraction: 5 - 2 = 3
Multiplication: 3 * 4 = 12
Division: 10 / 2 = 5.0
```

## Example

You can also use the `Calculator` class in your own scripts:

```python
from calculator import Calculator

calc = Calculator()
print(calc.add(10, 5))  # Output: 15
print(calc.subtract(10, 5))  # Output: 5
print(calc.multiply(10, 5))  # Output: 50
print(calc.divide(10, 5))  # Output: 2.0
```

## License

This project is licensed under the MIT License.