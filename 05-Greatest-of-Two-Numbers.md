## [Greatest of the Two Number](https://prepinsta.com/c-plus-plus/cpp-program-to-find-the-greatest-of-two-numbers/)


``` Using If-else Statement ```
```cpp
#include<bits/stdc++.h>
using namespace std;

int main(){

int n1, n2;
cin>>n1>>n2;

if(n1==n2){
    cout<< "Both are equal" << endl;
}
else if ( n1>n2){
    cout<< n1 << " is greater than" << n2<<endl;
}
else{
    cout<< n2<< " is greater than " << n1<< endl;
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
int n1, n2;
cin>>n1>>n2;
int largest;

if(n1==n2){
    cout<< " Both are equal"<<endl;
}

else{
    largest = n1 > n2 ? n1 : n2;
    cout<< largest<< " It is largest"<<endl;
}
    return 0;
}

// T.C = O(1)
// S.C = O(1)

```

``` Using inbuilt max() function ```
``` cpp

#include<bits/stdc++.h>
using namespace std;

int main(){

int n1, n2;
cin>>n1>>n2;

if(n1 == n2){
    cout<< "Both are equal" << endl;
}

else{
int largest = max(n1,n2);
cout<< largest << " It is largest"<<endl;
}

    return 0;
}

// T.C  = O(1)
// S.C = O(1)
```
