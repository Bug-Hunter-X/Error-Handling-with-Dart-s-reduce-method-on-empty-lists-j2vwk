# Dart Reduce Method Error Handling

This repository demonstrates a common error encountered when using the `reduce` method in Dart with an empty list. The `reduce` method requires at least one element to perform its operation; attempting to use it on an empty list results in an error.

The `bug.dart` file contains code that reproduces this error. The `bugSolution.dart` file provides a solution to handle this scenario gracefully.

## How to Reproduce

1. Clone this repository.
2. Run the `bug.dart` file using a Dart compiler.
3. Observe the error message.

## Solution

The solution involves adding a check to ensure the list is not empty before calling `reduce`.  This is shown in `bugSolution.dart`.