# Tuple

A tuple is a collection of values that can have different types. It is immutable,
which means that once it is created, it cannot be changed. It is created using
parentheses.

You can access the elements of tuple via the index: `tuple.0`, `tuple.1`, etc.

A tuple can be destructed via syntax like `let (a,b) = tuple`, where the `tuple` on
the right side is a tuple with two elements, and `a` and `b` are the variables to
store the elements. This is a special use case of *pattern matching* which we will
introduce in a later chapter.

It's common to use a tuple to return multiple values from a function.

