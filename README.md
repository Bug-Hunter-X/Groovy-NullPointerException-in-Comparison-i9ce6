# Groovy NullPointerException in Comparison

This example demonstrates a common issue in Groovy related to null comparisons.  Groovy's dynamic typing allows for flexible code, but it can lead to unexpected `GroovyCastException` exceptions when comparing null values to numbers.

The `bug.groovy` file contains a simple function that aims to return the larger of two numbers.  However, if either input is null, a runtime exception occurs.

The solution (`bugSolution.groovy`) provides a robust way to handle null values using the Elvis operator or safe navigation operator, preventing the exception.