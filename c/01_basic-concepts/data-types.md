## Basic Data Types

The data type specifies the size and type of information the variable will store.

In this tutorial, we will focus on the most basic ones:

| Data Type | Size         | Description                                                  | Example |
| --------- | ------------ | ------------------------------------------------------------ | ------- |
| `int`     | 2 or 4 bytes | Stores whole numbers, without decimals                       | `1`     |
| `float`   | 4 bytes      | Stores fractional numbers, containing one or more decimals. Sufficient for  storing 6-7 decimal digits | `1.99`  |
| `double`  | 8 bytes      | Stores fractional numbers, containing one or more decimals. Sufficient for  storing 15 decimal digits | `1.99`  |
| `char`    | 1 byte       | Stores a single character/letter/number, or ASCII values     | `'A'`   |



## Basic Format Specifiers

There are different format specifiers for each data type. Here are some of  them:

| Format Specifier | Data Type                                                    |
| ---------------- | ------------------------------------------------------------ |
| `%d` or `%i`     | `int`                                                        |
| `%f` or `%F`     | `float`                                                      |
| `%lf`            | `double`                                                     |
| `%c`             | `char`                                                       |
| `%s`             | Used for **[strings](https://www.w3schools.com/c/c_strings.php) (text)**, which you will learn more about in a later chapter |



# Character (char) Types

The `char` data type is used to store a  **single** character.

The character must be surrounded by single quotes, like 'A' or 'c', and we use the `%c` format specifier to print it

```c
char myGrade = 'A';
printf("%c", myGrade); 
```

Alternatively, if you are familiar with ASCII, you can use ASCII values  to display certain characters. Note that these values are not surrounded by quotes (`''`),  as they are numbers:



```c
char a = 65, b = 66, c = 67;
printf("%c", a);
printf("%c", b);
printf("%c", c); 
```



# Numeric Types

Use `int` when you need to store a whole number without decimals, like 35 or 1000, and `float` or `double` when you need a floating point number (with decimals), like 9.99 or 3.14515



## int

```c
int myNum = 1000;
printf("%d", myNum); 
```

## float

```c
float myNum = 5.75;
printf("%f", myNum); 
```

## double

```c
double myNum = 19.99;
printf("%lf", myNum); 
```





# References

* https://www.w3schools.com/c/c_data_types.php
