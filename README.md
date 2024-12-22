# Ruby Bug: Bypassing Accessor Methods
This example demonstrates a common, yet subtle, error in Ruby: directly manipulating instance variables using `instance_variable_set` and `instance_variable_get`. While this might seem convenient, it undermines the principles of encapsulation and can create hard-to-debug issues.

The `bug.rb` file contains code that shows how modifying instance variables directly bypasses accessor methods.  The solution, `bugSolution.rb`, showcases a better approach using accessor methods to maintain the integrity and predictability of the object's state.