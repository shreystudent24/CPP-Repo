---
title: Addition and Subtraction
tags: math
expertise: beginner
---

- Calculates the sum of two numbers.
- The program takes two numbers from user and store it in first_number,second_number and return its sum in sum variable .

```cpp
#include <iostream>
using namespace std;

int main() {

  int first_number, second_number, sum;
    
  cout << "Enter two integers: ";
  cin >> first_number >> second_number;

  // sum of two numbers in stored in variable sumOfTwoNumbers
  sum = first_number + second_number;

  // prints sum 
  cout << first_number << " + " <<  second_number << " = " << sum;     

  return 0;
}
```