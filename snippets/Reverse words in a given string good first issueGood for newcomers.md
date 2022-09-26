---
title: Reverse words in a given string
tags: String
expertise: beginner
---

-Given a String S, reverse the string without reversing its individual words. Words are separated by space.
-Input: i.like.this.program.very.much
-Output: much.very.program.this.like.i

```cpp
#include <iostream>
using namespace std;
class Solution
{
public:
//Function to reverse words in a given string.
string reverseWords(string S)
{
// code start
int n = s.size();
int i=0,j=0;
while(i<n)
{
while(i<n && s[i] != '.') i++;
reverse(s.begin()+j , s.begin()+i);
j=i+1;
i++;
}
reverse(s.begin() , s.end());
return s;
}
};
int main()
{
int t;
cin >> t;
while (t--)
{
string s;
cin >> s;
Solution obj;
cout<<obj.reverseWords(s)<<endl;
}
}
```
