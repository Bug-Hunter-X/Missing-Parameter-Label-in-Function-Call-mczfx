# Missing Parameter Label in Function Call

This example demonstrates a common error in Swift: forgetting to include parameter labels when calling a function that expects them.  Swift's type system relies on parameter labels to disambiguate arguments, especially when functions have multiple parameters of the same type.  Failing to use labels leads to compiler errors.

The `bug.swift` file shows the erroneous code, while `bugSolution.swift` provides the corrected version.

This is a subtle but frequent issue, particularly when working with functions containing multiple arguments.  Paying attention to parameter labels in Swift code is crucial for avoiding unexpected compiler errors.