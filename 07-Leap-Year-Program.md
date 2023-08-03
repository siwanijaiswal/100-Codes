## [Leap Year Program](https://prepinsta.com/cpp-program/cpp-program-to-check-whether-a-year-is-a-leap-year-or-not/)


``` Using If-else Statement ```
```cpp

#include<bits/stdc++.h>
using namespace std;

int main(){
    
    int year;
    cin>>year;

    if(year%400 == 0 || (year%4 ==0 && year%100 != 0)){
        cout<< "It is leap year"<<endl;
    }

    else{
        cout<< "It is not leap year"<<endl;
    }
    return 0;

}

 T.C = O(1)
 S.C = O(1)
```
