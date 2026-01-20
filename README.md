# pycak
Python3 (PEP 8 compliant except for long lines) / C++ polyglot :rabbit2:

Run with `python3 pycak` or compile with `g++ -x c++ pycak -o pycak.out` and then run with `./pycak.out`

- Dropped `-Wall -Wextra -Werror` "support" :sob:
- Dropped full PEP 8 compliance (long lines)
- Now supports nested function calls of the form `f1(f2(arg1, arg2), arg3)`, the `f1(arg1, f2(arg2, arg3))` variant compiles but returns incorrect results under C++.
