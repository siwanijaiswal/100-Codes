## [Palindrome Program](https://prepinsta.com/cpp-program/cpp-program-to-check-whether-a-number-is-palindrome-or-not/)

```cpp
#include<bits/stdc++.h>
using namespace std;

void solve(){
    int num;
    cin>>num;

    int reverse = 0;
    int lastdigit;
   int temp = num;

    while(temp!=0){
        lastdigit = temp%10;
        reverse = reverse * 10 + lastdigit;
        temp = temp/10;
    }
    if(num == reverse){
        cout<< "It is palindrome"<<endl;
    }
    else{
        cout<< "It is not palindrome"<<endl;
    }
}
int main(){
 solve();
    return 0;
}

//T.C= O(N)
// S.C = O(1)
```
