# shitcode
A piece of spaghetti code to detect if a year is leap.

The code is in javascript, it is already embedded into the HTML file. It is a regular expression which tests for an even digit + digit divisible by 4 or an odd digit + digit which is 2 mod 4 at the end of the string, with the exception for years divisible by 100 but not 400, which are not leap in Gregorian calendar, which is implemented with optional skipping of the last two zeros. With this addition, combination 00 is excluded from the basic logic, so years ending in four zeros are treated separately.

The page is published at https://andrij-ghorbunov.github.io/shitcode/ .