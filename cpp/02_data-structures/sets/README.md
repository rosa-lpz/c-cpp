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

### Example

```c++
  // Create a set called cars that will store strings
  set<string> cars;
```





# References

* https://www.w3schools.com/cpp/cpp_sets.asp