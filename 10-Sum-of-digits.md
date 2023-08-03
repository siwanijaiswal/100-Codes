## [Sum of digits of Number](https://prepinsta.com/cpp-program/cpp-program-to-find-the-sum-of-digits-of-a-number/)

```cpp
#include<bits/stdc++.h>
using namespace std;

void solve(){
    int num; 
    cin>>num;
    int sum = 0;
   
   while(num!=0){
    sum = sum + num%10;
    num= num/10;
   }

   cout<< sum<<endl;
}
int main(){
 solve();

    return 0;
}
// T.C = O(N)
// S.C = O(1)
```
