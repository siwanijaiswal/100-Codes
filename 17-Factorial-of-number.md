## [Factorial of a Number](https://prepinsta.com/cpp-program/to-find-the-factorial-of-a-number/)

```cpp
#include<bits/stdc++.h>
using namespace std;

int factorial (int n){
    if(n==0){
        return 1;
    }
    return n* factorial(n-1);
}

int main(){
int n;
cin>>n;
 
 int fact = factorial(n);
 cout<< fact<<endl;

    return 0;
}

//T.C =O(n)
// S.C =O(1)

```## [Factorial of a Number](https://prepinsta.com/cpp-program/to-find-the-factorial-of-a-number/)

```cpp
#include<bits/stdc++.h>
using namespace std;

int factorial (int n){
    if(n==0){
        return 1;
    }
    return n* factorial(n-1);
}

int main(){
int n;
cin>>n;
 
 int fact = factorial(n);
 cout<< fact<<endl;

    return 0;
}

//T.C =O(n)
// S.C =O(1)

```