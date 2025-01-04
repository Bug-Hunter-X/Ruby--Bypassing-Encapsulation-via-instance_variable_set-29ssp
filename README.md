# Ruby Encapsulation Bug

This example demonstrates a common coding error in Ruby that violates encapsulation principles.  Directly manipulating instance variables using `instance_variable_set` or `instance_variable_get` can introduce subtle bugs and make code harder to maintain and debug.  It's better to use methods to access and modify instance variables for better control and predictability.

## Bug:
The `bug.rb` file showcases the problem where the instance variable `@value` is accessed and modified directly, which is generally bad practice. 

## Solution:
The `bugSolution.rb` file presents a better approach by using a setter method to modify the `@value` variable, providing a layer of abstraction and improving the code's maintainability.
