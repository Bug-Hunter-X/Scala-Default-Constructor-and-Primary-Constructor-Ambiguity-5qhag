# Scala Default Constructor Issue

This repository demonstrates a potential pitfall in Scala when using default parameter values within the primary constructor and calling that primary constructor from a secondary (auxiliary) constructor. 

The `bug.scala` file contains code exhibiting the problem. The `bugSolution.scala` file offers a clearer, less ambiguous approach.

The core issue is how Scala resolves the call to the primary constructor from the auxiliary constructor when parameters might be implicitly set or ignored. Understanding these implications is crucial for clean and predictable code.