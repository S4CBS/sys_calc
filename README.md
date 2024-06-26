# sys_calc
# Number Conversion and IEEE 754 Representation

This project includes functions for:

1. Converting floating-point binary numbers to decimal.
2. Converting floating-point octal numbers to decimal.
3. Converting floating-point hexadecimal numbers to binary.
4. Converting floating-point numbers to hexadecimal representation in IEEE 754 format (single precision).

## Usage

To use the conversion functions, simply call the respective function with the number string in the desired number system.

To convert floating-point numbers to hexadecimal representation, use `float_to_hex_single(f, d)`, where `f` is the floating-point number, and `d` is the bias (default is 127).

## Examples

```python
binary_float_to_decimal('1101.101')
octal_float_to_decimal('17.45')
hex_to_binary('A.B')
float_to_hex_single(3.14)
