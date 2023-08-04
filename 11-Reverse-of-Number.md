## [Reverse of a Number](https://prepinsta.com/cpp-program/cpp-program-to-find-the-reverse-of-a-number/)


```cpp
#include<bits/stdc++.h>
using namespace std;

void solve(){
 int lastdigit;
 int reverse = 0;
    int num;
    cin>>num;

    while(num!=0){
        lastdigit = num%10;
        reverse = reverse*10 + lastdigit;
        num =  num/10;
    }
    cout<< "Reversed number is"<< reverse<< endl;
}

int main(){
    
solve();
    return 0;
}

// T.C = O(N)
// S.C = O(1)

```## [Reverse of a Number](https://prepinsta.com/cpp-program/cpp-program-to-find-the-reverse-of-a-number/)


```cpp
#include<bits/stdc++.h>
using namespace std;

void solve(){
 int lastdigit;
 int reverse = 0;
    int num;
    cin>>num;

    while(num!=0){
        lastdigit = num%10;
        reverse = reverse*10 + lastdigit;
        num =  num/10;
    }
    cout<< "Reversed number is"<< reverse<< endl;
}

int main(){
    
solve();
    return 0;
}

// T.C = O(N)
// S.C = O(1)

```