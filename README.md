# Shamir's Secret Sharing - Simplified Polynomial Solver

## Problem Overview

This project implements a simplified version of Shamir's Secret Sharing, which solves for the constant term 'c' of a polynomial using Lagrange Interpolation. 

## How it Works

Given a set of points `(x, f(x))` on a polynomial of degree `m`, the program uses Lagrange Interpolation to find the polynomial's constant term `c` (i.e., `f(0)`).

## Input Format

You need to provide a set of points and their corresponding base systems (e.g., binary, decimal). The program will:
- Convert these values to base 10.
- Interpolate the polynomial and solve for `c`.

## Running the Code

1. Clone the repository.
2. Compile the Java code using any Java environment or IDE.
3. Run the program to get the constant term `c`.

## Example

For the input points:
- f(1) = 4 (base 10)
- f(2) = 111 (base 2)
- f(3) = 12 (base 10)
- f(6) = 213 (base 4)

The output will be the constant term `c` of the polynomial.
