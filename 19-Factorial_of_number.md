## [Factorial of a Number](https://prepinsta.com/cpp-program/to-find-the-factorial-of-a-number/)

```Method 1- Recursive```
```cpp
#include<bits/stdc++.h>
using namespace std;

int factorial(int n){
    if(n==0){
        return 1;
    }
    return n* factorial(n-1);
}

int main(){

int n;
cin>>n;

int ans = factorial(n);
cout<< "factorial is: "<< ans<<endl;
    return 0;
}
// T.C = O(N)
// S.C = O(1)
```
``` Method 2- Iterative```
```cpp
 #include<bits/stdc++.h>
 using namespace std;

 int main(){
    int n;
    cin>>n;

    int fact = 1;

    for(int i=1; i<=n;i++){
        fact = fact * i;
    }
    cout<< "Factorial is: "<<fact<<endl;

    return 0;
 }

 // T.C = O(N)
 // S.C = O(1)
```## [Factorial of a Number](https://prepinsta.com/cpp-program/to-find-the-factorial-of-a-number/)

```Method 1- Recursive```
```cpp
#include<bits/stdc++.h>
using namespace std;

int factorial(int n){
    if(n==0){
        return 1;
    }
    return n* factorial(n-1);
}

int main(){

int n;
cin>>n;

int ans = factorial(n);
cout<< "factorial is: "<< ans<<endl;
    return 0;
}
// T.C = O(N)
// S.C = O(1)
```
``` Method 2- Iterative```
```cpp
 #include<bits/stdc++.h>
 using namespace std;

 int main(){
    int n;
    cin>>n;

    int fact = 1;

    for(int i=1; i<=n;i++){
        fact = fact * i;
    }
    cout<< "Factorial is: "<<fact<<endl;

    return 0;
 }

 // T.C = O(N)
 // S.C = O(1)
```