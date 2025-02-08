# Unexpected Data Type Handling in VBScript Function

This example demonstrates a subtle issue with implicit type conversion and function return values in VBScript.  The function `f` is designed to return an integer (-1, 0, or 1) depending on the input. However, the implicit type handling of VBScript can lead to unexpected results, particularly when combining different data types and assignments within a function.

The `bug.vbs` file contains the erroneous code. The solution, provided in `bugSolution.vbs`, explicitly declares the return type to avoid ambiguity and ensure correct behavior.  This highlights the importance of careful type management in VBScript, especially when functions are expected to return a variety of data types.