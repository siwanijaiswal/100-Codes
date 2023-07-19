## [Find the Sum of Numbers in a Given Interval](https://prepinsta.com/cpp-program/to-find-the-sum-of-numbers-in-a-given-range/)


``` Brute Force ```
```cpp
#include<bits/stdc++.h>
using namespace std;

int main(){
    int n1,n2;
    cin>>n1>>n2;

    int sum = 0;
    for(int i=n1; i<=n2; i++){
        sum = sum + i;
    }
    cout<< sum<<endl;
  return 0;
}

// T.C = O(N)
// S.C = O(1)

```

``` Using Formula ```
``` cpp

#include<bits/stdc++.h>
using namespace std;

int main(){
    int n1,n2;
    cin>>n1>>n2;

    int sum = n2*(n2+1)/2 - n1*(n1+1)/2 + n1;
    cout<< sum<<endl;
     
    return 0;
}

// T.C = O(1)
// S.C = O(1)

```

``` Using Recursion ```
``` cpp

#include<bits/stdc++.h>
using namespace std;

int Calsum(int n1, int n2){
    if(n1>n2)
    return 0;

    return n1 + Calsum(n1 + 1, n2);
}

int main(){
int n1,n2;
cin>>n1>>n2;
int sum = Calsum(n1 , n2);

cout<< sum<<endl;
    return 0;
}

// T.C = O(n)
// S.C = O(1)

```## [Find the Sum of Numbers in a Given Interval](https://prepinsta.com/cpp-program/to-find-the-sum-of-numbers-in-a-given-range/)


``` Brute Force ```
```cpp
#include<bits/stdc++.h>
using namespace std;

int main(){
    int n1,n2;
    cin>>n1>>n2;

    int sum = 0;
    for(int i=n1; i<=n2; i++){
        sum = sum + i;
    }
    cout<< sum<<endl;
  return 0;
}

// T.C = O(N)
// S.C = O(1)

```

``` Using Formula ```
``` cpp

#include<bits/stdc++.h>
using namespace std;

int main(){
    int n1,n2;
    cin>>n1>>n2;

    int sum = n2*(n2+1)/2 - n1*(n1+1)/2 + n1;
    cout<< sum<<endl;
     
    return 0;
}

// T.C = O(1)
// S.C = O(1)

```

``` Using Recursion ```
``` cpp

#include<bits/stdc++.h>
using namespace std;

int Calsum(int n1, int n2){
    if(n1>n2)
    return 0;

    return n1 + Calsum(n1 + 1, n2);
}

int main(){
int n1,n2;
cin>>n1>>n2;
int sum = Calsum(n1 , n2);

cout<< sum<<endl;
    return 0;
}

// T.C = O(n)
// S.C = O(1)

```