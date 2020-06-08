# Delegate C++

Delegate C++ is a single header, lightweight and easy to use abstraction for storing callbacks.

# Using Delegate C++

You can use delegate C++ by creating an instance of Delegate, adding in your functions, and calling Invoke();

# Important Information

You can find a basic example of Delegate C++ in example.cpp

Delegate C++ uses 2 types to store functions. 

1. DelFunctions - A reference to multiple functions.
2. DelFunction - A reference to a single function.

These are used as parameters and return values for all Delegate C++ functions and systems, so make sure you use these.

Delegate C++ does not inherit from, but is based heavily off of the <std::vector> type.
At its base, Delegate C++ uses an <std::vector> of <std::function> to store its data.

You can assign DelFunctions(s) them the same way you would assign an std::vector.
