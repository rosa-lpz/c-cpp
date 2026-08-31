# find() in C++ STL

std::find() is a standard algorithm provided by the [C++ Standard Template Library (STL)](https://www.geeksforgeeks.org/cpp/the-c-standard-template-library-stl/). It is used to find the first occurrence of a given value in a specified range. The function works with containers that provide iterators, such  as arrays, vectors, lists, and deques.





```c++
#include <iostream>
#include <vector>
#include <algorithm>
using namespace std;

int main() {
    vector<int> v = {1, 3, 6, 2, 9};

    // Sorting the vector
    sort(v.begin(), v.end());

    // Search for element 6
    auto it = find(v.begin(), v.end(), 6);

    // Print index
    cout << distance(v.begin(), it);

    return 0;
}
```

