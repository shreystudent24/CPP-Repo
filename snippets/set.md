---
title: Set  
tags: STL
expertise: beginner
---

 Sets are a type of associative container in which each element has to be unique because the value of the element identifies it. 

```cpp
#include <iostream>
#include <set>

int main()
{
std::set<char> a;
a.insert('P');
a.insert('R');
a.insert('G');
for(auto& str: a)
{
	std::cout << str << ' ';
}
std::cout << '\n';
return 0;
}

```

