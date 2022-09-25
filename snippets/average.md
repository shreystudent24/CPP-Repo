---
title: Average
tags: math
expertise: beginner
cover: blog_images/digital-nomad-15.jpg
firstSeen: 2018-01-27T07:16:41+02:00
lastUpdated: 2020-11-02T19:27:07+02:00
---

Calculates the average of two or more numbers.

- Use `sum()` to sum all of the `args` provided, divide by `len()`.
```cpp
int sum(int arr[], int getArrayLength)
{ 
   int sum=0;
  for(int i=0; i<getArrayLength; i++) sum+=arr[i]; 
  return sum;
}
```

```cpp
int average(int arr[], int getArrayLength){
		
	return sum(arr, getArrayLength)/getArrayLength;
}
```

```py
	int arr[] = {1,2,3,4,5};	
	int getArrayLength = sizeof(arr) / sizeof(int);
  cout<<average(arr,getArrayLength); // 3 
```
