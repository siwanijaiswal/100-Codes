## [Finding Nth Term of Fibonacci series](https://prepinsta.com/cpp-program/finding-the-nth-term-of-the-fibonacci-series/)

```cpp
#include<bits/stdc++.h>
using namespace std;

int fibonacci(int n){
    if(n<=1){
        return n;
    }
    return fibonacci(n-1)+fibonacci(n-2);
}

int main(){
    int n;
    cin>>n;
   cout<< fibonacci(n)<<endl;
    return 0;
}

//T.C = O(2^n)
// S.C = O(n)
```
