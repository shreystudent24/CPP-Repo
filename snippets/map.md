---
title: Map  
tags: STL
expertise: beginner
---

Maps are associative containers that store elements in a mapped fashion. Each element has a key value and a mapped value. 

```cpp
// CPP Program to demonstrate the implementation in Map
#include <iostream>
#include <iterator>
#include <map>
using namespace std;

int main()
{

	// empty map container
	map<int, int> map1;

	// insert elements in random order
	map1.insert(pair<int, int>(1, 40));
	map1.insert(pair<int, int>(2, 30));
	map1.insert(pair<int, int>(3, 60));
	map1.insert(pair<int, int>(4, 20));
	map1.insert(pair<int, int>(5, 50));
	map1.insert(pair<int, int>(6, 50));
	
	map1[7]=10;	 // another way of inserting a value in a map
	

	// printing map map1
	map<int, int>::iterator itr;
	cout << "\nThe map map1 is : \n";
	cout << "\tKEY\tELEMENT\n";
	for (itr = map1.begin(); itr != map1.end(); ++itr) {
		cout << '\t' << itr->first << '\t' << itr->second
			<< '\n';
	}
	cout << endl;

	return 0;
}


```

