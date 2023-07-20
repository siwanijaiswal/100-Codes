## [Greatest of three numbers](https://prepinsta.com/cpp-program/to-find-the-greatest-of-three-numbers/)


``` Using If-else Statement ```
```cpp
#include<bits/stdc++.h>
using namespace std;

int main(){
 int n1,n2,n3;
 cin>>n1>>n2>>n3;

 if((n1>n2) && (n1>n3)){
    cout<< n1<< "  is greatest"<<endl;
 }

 else if((n2>n3) && (n2>n1)){
    cout<< n2<< " is greatest"<<endl;
 }

 else{
    cout<< n3 << " is greatest"<<endl;
 }
    return 0;
}

// T.C = O(1)
// S.C = O(1)

```

```Using Ternary Operator ```
``` cpp
#include<bits/stdc++.h>
using namespace std;

int main(){
    int n1,n2,n3;
    cin>>n1>>n2>>n3;

    int temp, result;

    temp = n1>n2 ? n1:n2;
    result = temp > n3 ? temp: n3;

    cout<< result<< " is greatest"<<endl;

    return 0;
}
// T.C = O(1)
// S.C = O(1)
```

``` Using internal inbuilt max function ```
``` cpp

#include<bits/stdc++.h>
using namespace std;

int main(){

 int n1, n2,n3;
 cin>>n1>>n2>>n3;

 int largest = max(n1, max(n2,n3));
 cout<< largest<< " is greatest"<<endl;

    return 0;
} 

// T.C  = O(1)
// S.C = O(1)
```
