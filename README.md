BesselFunctions
===============

Numerical algorithms for fast and controlled precision generation of Bessel type functions.

Try something like:
double j0(double x);
double j1(double x);
double jn(int n, double x);
double y0(double x);
double y1(double x);
double yn(int n, double x);

Where:
Bessel functions solve certain types of differential equations. The j0(), j1(), and jn() functions are Bessel functions of the first kind for orders 0, 1, and n, respectively. The y0(), y1(), and yn() functions are Bessel functions of the second kind for orders 0, 1, and n, respectively.
The argument x must be positive. The argument n should be greater than or equal to zero. If n is less than zero, it will be a negative exponent.