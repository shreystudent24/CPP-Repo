---
title: XOR of all the elements in an array
tags: bitwise, array
expertise: intermediate
cover: https://cdn.educba.com/academy/wp-content/uploads/2020/11/XOR-gate-3.jpg
---

XOR ia a bitwise operator.

- XOR or eXclusive OR is a logical operation that compares the input values (bits) and generates the output value (bit). 
- If the input values are the same, the output is 0 (or false). 
- If the input values are different, the result is 1 (or true).


```cpp
int exor(int arr[], int n)
{
    int xor_arr = 0;
    
    for (int i = 0; i < n; i++) {
        // finding XOR
        xor_arr = xor_arr ^ arr[i];
    }
 
    return xor_arr;
}
```

```cpp
int arr[] = { 2, 5, 6, 8, 14 };
int n = sizeof(arr) / sizeof(arr[0]);
 
// Function call
cout << exor(arr, n) << endl;
```
