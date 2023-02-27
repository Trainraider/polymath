# Poly Math

Do math operations on polynomials.

# Usage

polymath [-h] poly1 poly2 op

Do math with polynomials

positional arguments:  
  poly1       First polynomial  
  poly2       Second polynomial  
  op          Operation, +, -, /, or *  

options:
  -h, --help  show this help message and exit

```bash
$ polymath "x**3*y**3" "x*y" "+"
Sum: x**3*y**3 + x*y
$ polymath "x**3*y**3" "x*y" "-"
Difference: x**3*y**3 - x*y
$ polymath "x**3*y**3" "x*y" "*"
Product: x**4*y**4
$ polymath "x**3*y**3" "x*y" "/"
Quotient: x**2*y**2
Remainder: 0
```

### Unix, Linux, MacOS, etc.

 After installing sympy, the polymath source file is ready to be run as a script directly on any Unix-like system with python installed and python3 in the PATH. You may need to `chmod +x polymath` if it doesn't have permission to execute however.

### Windows

Install python 3 and make sure it is in your path. Install sympy Open a terminal like cmd and enter the src folder. Run `python polymath "x**2*y**2" "x*y" "/"` for example.
