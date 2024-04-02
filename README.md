# math modf
import math modf

* Input: A real number
* Output: A tuple(immutable list in python) consisting of two floating-point numbers

This function takes one number x as an argument and returns a tuple(f,i) where f represents the integer part of x.

solution:

    (0.7599999999999998, 14.0)

# math hypotenuse
* Input: Two real numbers
* Return Type: A floating-point number

This function takes two inputs. perpendicular and base of a right-angled triangle and it returns the hypotenuse of the right-angled triangle using the pythagorean theorem.

solution:

    h= 8.602325267042627
# math gamma

* Input: A real number
* Return Type: A floating-point number

This function takes one number x as an argument and returns the value of the gamma function of x.

solution:

     g= 5.2993297338097065
     
# math degrees(x)

* Input: A real number
* Return type: A floating-point number

This function takes one number x in radians as input and returns the converted value of x in degrees.
* math.degrees(math.pi)=180.o

solution:

    d= 180.0
# math remainder
import  math.remainder

math.remainder(x,y)

* Input: Two real numbers.
* Return type: A floating-point number.

This function takes two numbers x and y as arguments and returns the remainder of x with respect to y. It means that it returns the value v=x-n*y where n=[x/y], here []-> greatest integer function (floor function).

solution:

     0.9000000000000012
# math functions
import math

The dir( ) Function

A sorted list of strings comprising the identifiers of the functions defined by a module is what the built-in method dir() delivers.
The list includes the names of modules, each specified constants, functions, and methods. Here is a straightforward illustration:

solution:

        ['__doc__', '__loader__', '__name__', '__package__', '__spec__', 'acos', 'acosh', 'asin', 'asinh', 'atan', 'atan2', 'atanh', 'cbrt', 'ceil', 'comb', 'copysign', 'cos', 'cosh', 'degrees', 'dist', 'e', 'erf', 'erfc', 'exp', 'exp2', 'expm1', 'fabs', 'factorial', 'floor', 'fmod', 'frexp', 'fsum', 'gamma', 'gcd', 'hypot', 'inf', 'isclose', 'isfinite', 'isinf', 'isnan', 'isqrt', 'lcm', 'ldexp', 'lgamma', 'log', 'log10', 'log1p', 'log2', 'modf', 'nan', 'nextafter', 'perm', 'pi', 'pow', 'prod', 'radians', 'remainder', 'sin', 'sinh', 'sqrt', 'tan', 'tanh', 'tau', 'trunc', 'ulp']
# math ldexp
import math ldexp

math.ldexp(x,i)
* Input: A real number and an integer
* Return type: A floating-point number

This function takes a real number x and an integer i as arguments and returns the value of the expression x*2i.

solution:

       48.0
# math lcm
import math.lcm

* Input: Zero or more integers
* Return type: An integer

This function takes zero or more integer arguments. It returns the L.C.M. (least common multiple) of all the arguments passed in the function. If no argument is passed in the function then 0 is returned.

solution:

      24060
# math frexp
math.frexp

math.frexp(x)

* Input: Real number
* Return Type: A Tuple containing one floating-point number & one integer ( A tuple is simply an immutable list in python)

This function takes a real number x as an argument and returns a tuple with the first value as the mantissa(floating number) and the second value as the exponent(integer) i.e. it returns a tuple (m,e) such that x = m * 2e. Here, in this expression, the floating number m is known as the mantissa and the integer e is known as the exponent.

solution:

     (0.75, 4)
# Generate-Random-Floats
import math

Generate Random Floats

The random.random() function gives a float number that ranges from 0.0 to 1.0. There are no parameters required for this function.

random.random(): Returns the second random floating point value within(0.0 to 1) is returned.

