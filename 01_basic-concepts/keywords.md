# C++ Keywords



## Categorization of C++ 



| Category                  | Keywords                                                     |
| ------------------------- | ------------------------------------------------------------ |
| Data Types                | [bool](https://www.geeksforgeeks.org/cpp/cpp-booleans/), [char](https://www.geeksforgeeks.org/cpp/cpp-char-data-types/), [char8_t](https://www.geeksforgeeks.org/cpp/char8_t-data-type-in-cpp-20/), char16_t, char32_t, int, long, short, signed, unsigned, float, double, void, wchar_t |
| Control Flow              | [if](https://www.geeksforgeeks.org/cpp/c-c-if-else-statement-with-examples/), [else](https://www.geeksforgeeks.org/cpp/c-c-if-else-statement-with-examples/), [switch](https://www.geeksforgeeks.org/cpp/switch-statement-in-cpp/), case, [default](https://www.geeksforgeeks.org/cpp/default-arguments-c/), [for](https://www.geeksforgeeks.org/cpp/cpp-for-loop/), [while](https://www.geeksforgeeks.org/cpp/cpp-while-loop/), [do](https://www.geeksforgeeks.org/cpp/cpp-do-while-loop/), [break](https://www.geeksforgeeks.org/cpp/cpp-break-statement/), [continue](https://www.geeksforgeeks.org/cpp/continue-statement-cpp/), [goto](https://www.geeksforgeeks.org/cpp/goto-statement-in-cpp/) |
| Boolean & Null            | true, false, [nullptr](https://www.geeksforgeeks.org/cpp/understanding-nullptr-c/) |
| Memory Management         | new, [delete](https://www.geeksforgeeks.org/cpp/delete-in-c/), [sizeof](https://www.geeksforgeeks.org/cpp/cpp-sizeof-operator/), [alignas](https://www.geeksforgeeks.org/cpp/alignas-in-cpp-11/), [alignof](https://www.geeksforgeeks.org/cpp/alignof-operator-in-c/) |
| Classes & Structs         | class, [struct](https://www.geeksforgeeks.org/cpp/structures-in-cpp/), [union](https://www.geeksforgeeks.org/cpp/cpp-unions/), [enum](https://www.geeksforgeeks.org/cpp/enumeration-in-cpp/), [friend](https://www.geeksforgeeks.org/cpp/friend-class-function-cpp/), [mutable](https://www.geeksforgeeks.org/cpp/c-mutable-keyword/), [this](https://www.geeksforgeeks.org/cpp/this-pointer-in-c/) |
| Access Specifiers         | [public](https://www.geeksforgeeks.org/cpp/access-modifiers-in-c/), [private](https://www.geeksforgeeks.org/cpp/access-modifiers-in-c/), [protected](https://www.geeksforgeeks.org/cpp/access-modifiers-in-c/) |
| Functions & Modifiers     | [inline](https://www.geeksforgeeks.org/cpp/inline-functions-cpp/), [explicit](https://www.geeksforgeeks.org/cpp/use-of-explicit-keyword-in-cpp/), [virtual](https://www.geeksforgeeks.org/cpp/virtual-function-cpp/), override, [final](https://www.geeksforgeeks.org/cpp/c-final-specifier/), [constexpr](https://www.geeksforgeeks.org/cpp/understanding-constexper-specifier-in-cpp/), consteval, [constinit](https://www.geeksforgeeks.org/cpp/constinit-specifier-in-cpp-20/), operator, [typedef](https://www.geeksforgeeks.org/cpp/typedef-in-cpp/), using, [typename](https://www.geeksforgeeks.org/cpp/how-to-use-typename-keyword-in-cpp/) |
| Templates & Generics      | [template](https://www.geeksforgeeks.org/cpp/templates-cpp/), concept, requires |
| Exception Handling        | [try](https://www.geeksforgeeks.org/cpp/how-to-use-the-try-and-catch-blocks-in-cpp/), [catch](https://www.geeksforgeeks.org/cpp/how-to-use-the-try-and-catch-blocks-in-cpp/), throw, [noexcept](https://www.geeksforgeeks.org/cpp/noexcept-operator-in-cpp-11/) |
| Casting & Type Info       | [const_cast](https://www.geeksforgeeks.org/cpp/const_cast-in-c-type-casting-operators/), [dynamic_cast](https://www.geeksforgeeks.org/cpp/dynamic-_cast-in-cpp/), [reinterpret_cast](https://www.geeksforgeeks.org/cpp/reinterpret_cast-in-c-type-casting-operators/), [static_cast](https://www.geeksforgeeks.org/cpp/static_cast-in-cpp/), [decltype](https://www.geeksforgeeks.org/cpp/type-inference-in-c-auto-and-decltype/), [typeid](https://www.geeksforgeeks.org/cpp/typeid-operator-in-c-with-examples/) |
| Constants & Storage       | [const](https://www.geeksforgeeks.org/cpp/const-keyword-in-cpp/), [static](https://www.geeksforgeeks.org/cpp/static-keyword-cpp/), [static_assert](https://www.geeksforgeeks.org/cpp/understanding-static_assert-c-11/), [extern](https://www.geeksforgeeks.org/c/understanding-extern-keyword-in-c/), register, [thread_local](https://www.geeksforgeeks.org/cpp/thread_local-storage-in-cpp-11/), [volatile](https://www.geeksforgeeks.org/cpp/how-to-use-volatile-keyword-in-cpp/) |
| Modules / Export          | export, [namespace](https://www.geeksforgeeks.org/cpp/namespace-in-c/) |
| Coroutines (C++20)        | co_await, co_return, co_yield                                |
| Operators (alt spellings) | and, and_eq, or, or_eq, not, not_eq, bitand, bitor, compl, xor, xor_eq |
| Miscellaneous             | [asm](https://www.geeksforgeeks.org/cpp/c-asm-declaration/), [auto](https://www.geeksforgeeks.org/cpp/type-inference-in-c-auto-and-decltype/), [return](https://www.geeksforgeeks.org/cpp/return-statement-in-cpp-with-examples/), [sizeof](https://www.geeksforgeeks.org/cpp/cpp-sizeof-operator/) |

**Note**: The number of keywords C++ has evolved over time as new features were added to the language. **For example**, C++ 98 had 63 keywords, C++ 11 had 84 keywords.



## Keywords vs Identifiers

Keywords and Identifiers are the basic building  blocks of a C program. Keywords are reserved words with predefined  meanings, while identifiers are user-defined names used to identify  program elements.

- Keywords define the syntax and structure of the C language and cannot be used as names. 
- Identifiers are user-defined names given to variables, functions, arrays, structures, and other program elements.



| Feature                | Keyword                                           | Identifier                                             |
| ---------------------- | ------------------------------------------------- | ------------------------------------------------------ |
| Definition             | A reserved word with a predefined meaning in C.   | A user-defined name used to identify program elements. |
| Purpose                | Defines the syntax and structure of the language. | Names variables, functions, arrays, structures, etc.   |
| Defined By             | C Language                                        | Programmer                                             |
| Can Be Modified        | No                                                | Yes                                                    |
| Usage as Variable Name | Not Allowed                                       | Allowed                                                |
| Meaning                | Fixed and predefined.                             | Depends on the programmer's choice.                    |
| Lowercase or uppercase | It should be lowercase                            | It can be both upper and lowercase                     |
| Number Available       | Limited and predefined.                           | Unlimited (within naming rules).                       |
| Examples               | int, if, while, return                            | age, salary, display(), studentName                    |





# References

* [W3School - C++ Keywords ](https://www.w3schools.com/cpp/cpp_ref_keywords.asp)
* [GeeksForGeeks - C++ Keywords ](https://www.geeksforgeeks.org/cpp/cpp-keywords/)
* [GeeksForGeeks - Difference between Keyword and Identifier in C ](https://www.geeksforgeeks.org/c/difference-between-keyword-and-identifier/)
