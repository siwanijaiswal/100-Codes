 ## [Check if it is even or odd number](https://prepinsta.com/cpp-program/to-check-whether-a-number-is-even-or-odd/)

 ```Brute Force```

 ```cpp
 #include<bits/stdc++.h>
using namespace std;

int main(){
     int n;
     cout<< " Enter a number: ";
     cin>>n;

     if(n%2 ==0) cout<< " It is even number "<<endl;
     else cout<< " It is odd number "<<endl;

    return 0;
}
```

```Ternary Operators```
``` cpp

#include<bits/stdc++.h>
using namespace std;

int main(){
     int n;
     cout<< " Enter a number: ";
     cin>>n;
    //Checking if the number is divisible by 2
     (n%2 ==0) ? cout<< " It is even number ": cout<< " It is odd number "<<endl;

    return 0;
}
```

