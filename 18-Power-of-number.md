## [Power of a number](https://prepinsta.com/cpp-program/cpp-program-to-find-the-power-of-a-number/)

```Method 1- Using inbuilt function```
```cpp
#include<iostream>
#include<math.h>
using namespace std;

int main() 
{
    int base = 5;
    int expo1 = 2;
    
    double res1;
    res1 = pow(base, expo1);
    
    cout << base << " ^ " << expo1 << " = " << res1 << endl;
    return 0;
}

// T.C = O(1)
// S.C = O(1)

```
``` Method 2-Without using inbuilt function```
```cpp
#include<bits/stdc++.h>
using namespace std;

int main(){

int base;
cin>>base;
int exponent;
cin>>exponent;
int pow = 1;

// for(int i=1; i<=exponent; i++){
//     pow = pow* base;
// }

while(exponent!=0){
    pow = pow * base;
    exponent--;
}
cout<< "Power is "<<pow<<endl;
    return 0;
}

// T.C = O(exponent)
// S.C = O(1)
```## [Power of a number](https://prepinsta.com/cpp-program/cpp-program-to-find-the-power-of-a-number/)

```Method 1- Using inbuilt function```
```cpp
#include<iostream>
#include<math.h>
using namespace std;

int main() 
{
    int base = 5;
    int expo1 = 2;
    
    double res1;
    res1 = pow(base, expo1);
    
    cout << base << " ^ " << expo1 << " = " << res1 << endl;
    return 0;
}

// T.C = O(1)
// S.C = O(1)

```
``` Method 2-Without using inbuilt function```
```cpp
#include<bits/stdc++.h>
using namespace std;

int main(){

int base;
cin>>base;
int exponent;
cin>>exponent;
int pow = 1;

// for(int i=1; i<=exponent; i++){
//     pow = pow* base;
// }

while(exponent!=0){
    pow = pow * base;
    exponent--;
}
cout<< "Power is "<<pow<<endl;
    return 0;
}

// T.C = O(exponent)
// S.C = O(1)
```