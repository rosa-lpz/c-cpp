## Data Structures

Data structures are used to store and organize data. An [array](https://www.w3schools.com/cpp/cpp_arrays.asp) is an example of a data structure, which  allows multiple elements to be stored in a single variable.

C++ includes many other data structures as well, each is used to handle data  in different ways.

These are part of the C++ STL, which stands for The **S**tandard **T**emplate  **L**ibrary.

------

## C++ STL

STL is a library that consist of different **data structures** and  **algorithms** to effectively store and manipulate data.

If we say that data structures store data, we can say that algorithms are used to solve different problems,  often by searching through and manipulating those data structures.

Using the right data structure and algorithm makes your program run faster,  especially when working with lots of data.

The most common data structures are:

| Data Structure                                          | Description                                                  |
| ------------------------------------------------------- | ------------------------------------------------------------ |
| [Vector](https://www.w3schools.com/cpp/cpp_vectors.asp) | Stores elements like an [array](https://www.w3schools.com/cpp/cpp_arrays.asp) but can     dynamically change in size. Adding and removing of elements are usually done     at the end. Elements can be accessed by index. |
| [List](https://www.w3schools.com/cpp/cpp_list.asp)      | Stores elements sequentially, where each element is connected to the     next. Adding and removing of elements can be done at both ends. Not     accessible by index. |
| [Stack](https://www.w3schools.com/cpp/cpp_stacks.asp)   | Stores elements in a specific order, called LIFO (Last In, First Out),     where elements can only be added and removed from the top. Not accessible by     index. |
| [Queue](https://www.w3schools.com/cpp/cpp_queues.asp)   | Stores elements in a specific order, called FIFO (First In, First Out),     where elements are added at the end and removed from the front. Not     accessible by index. |
| [Deque](https://www.w3schools.com/cpp/cpp_deque.asp)    | Stores elements in a double-ended queue, where elements can be added and     removed from both ends. Elements can be accessed by index. |
| [Set](https://www.w3schools.com/cpp/cpp_sets.asp)       | Stores unique elements. Not accessible by index.             |
| [Map](https://www.w3schools.com/cpp/cpp_maps.asp)       | Stores elements in "key/value" pairs. Accessible by keys (not by index). |

Which one to use depends on your specific needs. One thing they all have in common is that you must include the  appropriate header file to use them:

### Example

```c++
  // Include the vector library
\#include <vector>
  
// Include the list library
\#include <list>

// Include the set   library
\#include <set>

// Include the map library
\#include <map>

// Include the stack library
\#include <stack>

//   Include the queue library
\#include <queue>
```




  

Here is an example of using vectors, after we have included the `<vector>` library:

### Example

```c++
  // Create a vector called cars that will store strings
vector<string> cars = {"Volvo", "BMW",   "Ford", "Mazda"};

// Print vector elements
  for (string car : cars) {
 cout << car << "\n";
}
```




  

The next chapters will explain how each data structure works and how to use them.

------



# References

https://www.w3schools.com/cpp/cpp_data_structures.asp
