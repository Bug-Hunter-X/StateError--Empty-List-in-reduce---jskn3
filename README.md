# StateError: Empty List in reduce()

This example demonstrates a common error when using the `reduce()` method on an empty list in Dart.  The `reduce()` method requires at least one element to perform the reduction; otherwise, it throws a `StateError`.  The solution shows how to handle this gracefully using a check for an empty list.

## Bug

The `bug.dart` file shows the error-causing code.  It attempts to use `reduce()` on an empty list, resulting in a `StateError`.

## Solution

The `bugSolution.dart` file presents a solution that checks if the list is empty before calling `reduce()`. This prevents the error by providing an alternative behavior for empty lists.