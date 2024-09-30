# Shamir's Secret Sharing Algorithm

## Description
This project implements a simplified version of Shamir's Secret Sharing algorithm. The objective is to find the constant term of a polynomial based on given roots and to identify any points that do not lie on the polynomial curve.

## Problem Statement
The task involves calculating the constant term \( c \) of a polynomial defined by its roots provided in JSON format. The polynomial can be represented as:

\[ f(x) = a_m x^m + a_{m-1} x^{m-1} + \ldots + a_1 x + c \]

### Input Format
- The input is provided in JSON format containing the roots, where each root has a base and a value that needs to be decoded.

