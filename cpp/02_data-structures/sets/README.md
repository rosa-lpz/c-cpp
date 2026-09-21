# Sets

A set stores unique elements where they:

- Are sorted automatically in ascending order.
- Are unique, meaning equal or duplicate values are ignored.
- Can be added or removed, but the value of an existing element cannot be changed.
- Cannot be accessed by index numbers, because the order is based on  sorting and not indexing.



To use a set, you have to include the `<set>` header file: 

```c++
// Include the set library
#include <set>
```

## Create a Set

To create a set, use the `set` keyword,  and specify the **type** of values it should store within angle brackets `<>`  and then the name of the set, like: `set<*type*>  *setName*`.

### Example - string set

```c++
  // Create a set called cars that will store strings
  set<string> cars;
```

If you want to add elements at the time of declaration, place them in a comma-separated list, inside curly braces `{}`:



```c++
// Create a set called cars that will store strings
set<string> cars = {"Volvo", "BMW", "Ford", "Mazda"};

// Print set elements
for (string car : cars) {
  cout << car << "\n";
}
```

Output

```bash
BMW
Ford
Mazda
Volvo 
```

The result above shows that the elements in the set are  sorted automatically. In this case, alphabetically, as we are working with strings.

### Example - Integer set



```c++
// Create a set called numbers that will store integers
set<int> numbers = {1, 7, 3, 2, 5, 9};

// Print set elements
for (int num : numbers) {
  cout << num << "\n";
}
```

Output

```bash
1
2
3
5
7
9
```

**Note:** The type of the set (e.g. `string` and `int` in   the examples above) cannot be changed after its been declared.

# References

* https://www.w3schools.com/cpp/cpp_sets.asp