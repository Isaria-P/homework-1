# Homework: Leap year

[What is a leap year?] In the Gregorian calendar, a leap year is year
that is evenly divisible by 4, unless it's evenly divisible by 100, in
which case it's only a leap year if the year is also evenly divisible
by 400. For example, 1997 was not a leap year as it's not divisible by
4. Nor was 1900 as it's not divisible by 400. 2000 was a leap year as it
meets both criteria.

Design a function that determines whether a given year is a leap year.
You are not allowed to use the modulo operator `%` nor any function from
the standard library to determine whether a number is evenly divisible
by another. Instead, create a helper function that continously substract
the divisor from the dividend while the dividend is greater than 0. If
the dividend ends up being 0, then you know it is divisible evenly by
the divisor.

Don't forget to test your functions using either doctests or `assert`
statements.

Once your program works as expected, use the built-in functions `input`
and `print` so that we can use it from the command-line.

[What is a leap year?]: https://www.youtube.com/watch?v=xX96xng7sAE
