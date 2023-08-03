## [Prime Number Program](https://prepinsta.com/cpp-program/prime-number/)


``` Optimization by break condition ```
```cpp

#include<bits/stdc++.h>
using namespace std;

void solve(){
    int num;
    cin>>num;

    bool isprime = true;

    if(num<2){
        isprime=false;
    }
 else{
    for(int i=2; i<num; i++){
       if(num%i == 0 ){
        isprime = false;
        break;
       }
    }
 }

 string result = isprime? "prime" : "notprime";
 cout<< result<< endl;
}

int main(){
solve();
    return 0;
}
//T.C = O(N)
// S.C = O(1)
```
