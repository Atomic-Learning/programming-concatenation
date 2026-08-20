In programming, concatenation is the operation of joining two or more data structures together to form a new data structure. Data structures such as strings, lists, and arrays, key-value collections, and even more complex data structures can be concatenated. Syntax varies between languages, but concatenation is often performed using the `+` operator.

Normally, only data structures of the same type can be concatenated together, although some languages may allow for concatenation of different types with specific rules.

Usually, the original data structures remain unchanged after concatenation, and a new data structure is created to hold the combined elements.

# String Example

```
string1 = "Hello, "
string2 = "world!"
combined_string = string1 + string2

print(combined_string) // Output: "Hello, world!"
print(string1) // Output: "Hello, "
print(string2) // Output: "world!"
```

# Array Example

```
array1 = [1, 2, 3]
array2 = [4, 5, 6]
combined_array = array1 + array2

print(combined_array) // Output: [1, 2, 3, 4, 5, 6]
print(array1) // Output: [1, 2, 3]
print(array2) // Output: [4, 5, 6]
```

# Concatenating Multiple Data Structures

Multiple data structures can often be concatenated in a single operation:

```
array1 = [1, 2]
array2 = [3, 4]
array3 = [5, 6]
combined_array = array1 + array2 + array3

print(combined_array) // Output: [1, 2, 3, 4, 5, 6]
```

# Uses

Concatenation is a fundamental operation in programming and is used in various contexts, such as:

* Building complex data structures from simpler ones.
* Combining strings for output or further processing.
* Merging lists or arrays to create a single collection of elements.
