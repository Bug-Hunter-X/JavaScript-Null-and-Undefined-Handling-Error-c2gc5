# JavaScript Null and Undefined Handling

This repository demonstrates a common error in JavaScript related to the handling of `null` and `undefined` values in function parameters.

## The Problem

Many JavaScript functions don't explicitly check for `null` or `undefined` inputs. This can lead to unexpected results or runtime errors when these values are passed as arguments. For example, attempting to access properties of a `null` or `undefined` object will throw a `TypeError`.

## The Solution

The solution is to always validate function parameters for `null` or `undefined` values before using them. This can be done with explicit checks using `===` for strict equality.  If `null` or `undefined` are detected, appropriate actions can be taken such as returning a default value or throwing an error.

## How to Use

1. Clone the repository: `git clone ...`
2. Navigate to the repository directory: `cd ...`
3. Open the `bug.js` file to see an example of incorrect null handling and `bugSolution.js` to see the correct implementation.
