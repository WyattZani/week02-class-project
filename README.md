Week 2 Class Project — Ohm's Law Calculator

This program calculates electrical current using Ohm's law. It reads two numbers from the terminal, a voltage in volts and a resistance in ohms, and prints the resulting current in amperes using the formula I = V / R.

The input is two numbers on standard input, the voltage first and the resistance second. On success the program prints "Current: " followed by the value and " A". If either value cannot be read as a number, or if the resistance is zero or negative, it prints "Invalid input" instead. For example, the input 12 4 produces "Current: 3 A", while the input 12 0 produces "Invalid input".

Building the program requires g++ with C++17 support and no external libraries. Compile it by creating a build directory and running g++ -std=c++17 -Wall -Wextra -pedantic src/main.cpp -o build/app, then run ./build/app. The build produces no errors and no warnings under those flags.

The acceptance tests live in the tests folder as pairs of input and expected-output files. Running bash test.sh compiles the program, feeds each input file in with redirection, and compares the result against the expected output using diff. It prints "All acceptance tests passed" when both tests succeed, and stops with a nonzero exit code at the first mismatch.
