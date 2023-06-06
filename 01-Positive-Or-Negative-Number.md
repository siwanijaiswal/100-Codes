  [Check if it is positive or negative number](https://prepinsta.com/cpp-program/cpp-program-to-check-whether-a-number-is-positive-or-negative/)

 ```Brute Force```

 ```cpp
 #include<bits/stdc++.h>
using namespace std;

int main(){
    int n;
    cout<< " Enter a number: ";
    cin>>n;

    if(n>0) cout<< " It is positive number "<<endl;

    else if(n<0) cout<< " It is negative number "<<endl;

    else cout<< " Zero " <<endl;
    return 0;
}
```

```Ternary Operators```
``` cpp

#include<bits/stdc++.h>
using namespace std;

int main(){
    int n;
    cout<< "Enter a number: ";
    cin>>n;

    if(n==0)  cout<< " Zero"; else(n>0) ? cout<< "It is positive number": cout<< " It is negative number";
  return 0;
}
```
 
