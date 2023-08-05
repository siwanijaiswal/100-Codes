## [Fibonacci Series Program](https://prepinsta.com/cpp-program/cpp-program-to-print-fibonacci-series-up-to-n-numbers/)


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
    for(int i=0; i<n; i++){
        cout<<fibonacci(i)<< " ";
    }
    return 0;
}

//T.C = O(2^n)
// S.C = O(n)

```## [Fibonacci Series Program](https://prepinsta.com/cpp-program/cpp-program-to-print-fibonacci-series-up-to-n-numbers/)


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
    for(int i=0; i<n; i++){
        cout<<fibonacci(i)<< " ";
    }
    return 0;
}

//T.C = O(2^n)
// S.C = O(n)

```