---
title: lower_bound 
tags: Algorithm
expertise: beginner
cover: blog_images/digital-nomad-15.jpg
firstSeen: 2018-01-27T07:16:41+02:00
lastUpdated: 2020-11-02T19:27:07+02:00
---

lower_bound returns an iterator pointing to the first element in the range [first,last) which has a value not less than ‘Element’. 


```cpp
// lower_bound in vector

#include <algorithm> // for lower_bound and sort
#include <iostream>
#include <vector> // for vector

using namespace std;

int main()
{
	int arr[] = { 5, 6, 7, 7, 6, 5, 5, 6 };

	vector<int> v(arr, arr + 8); // 5 6 7 7 6 5 5 6

	sort(v.begin(), v.end()); // 5 5 5 6 6 6 7 7

	vector<int>::iterator lower;
	lower = lower_bound(v.begin(), v.end(), 6);
	cout << "lower_bound for 6 at position "
         << (lower - v.begin() + 1) << '\n';

	return 0;
}
```

