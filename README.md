# pycak
Python3 (PEP 8 compliant except for long lines) / C++ polyglot :rabbit2:

Run with `python3 pycak` or compile with `g++ -Wall -Wextra -Werror -x c++ pycak -o pycak.out -lgmp -lgmpxx` and then run with `./pycak.out`

- Reimplemnted `-Wall -Wextra -Werror` "support" :smile:
- Added GMP as a dependency for arbitrary precision integer math
- Dropped full PEP 8 compliance (long lines)
- Implemented a "function" that calculates the factorial of X :smile:
- Supports nested function calls of the form `f1(f2(arg1, arg2), arg3)` (to a certain extent), the `f1(arg1, f2(arg2, arg3))` variant compiles but returns incorrect results under C++.
