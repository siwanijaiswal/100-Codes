## [Prime numbers in a range](https://prepinsta.com/cpp-program/cpp-program-to-find-prime-numbers-in-a-given-range/)



```cpp

#include<bits/stdc++.h>
using namespace std;

bool isprime(int n){
    int count =0;

  if(n<2){
    return false;
  }
  for(int i=2; i<n; i++){
    if(n%i ==0){
        return false;
    }
  }
  return true;
}

int main(){
    int lower, upper;
    lower = 1;
    upper = 100;

    for(int i = lower; i<upper; i++){
        if(isprime(i)){
            cout<< i<< " ";
        }
    }
    return 0;
}

// T.C = O(N^2)
// S.C = O(1)

```## [Prime numbers in a range](https://prepinsta.com/cpp-program/cpp-program-to-find-prime-numbers-in-a-given-range/)



```cpp

#include<bits/stdc++.h>
using namespace std;

bool isprime(int n){
    int count =0;

  if(n<2){
    return false;
  }
  for(int i=2; i<n; i++){
    if(n%i ==0){
        return false;
    }
  }
  return true;
}

int main(){
    int lower, upper;
    lower = 1;
    upper = 100;

    for(int i = lower; i<upper; i++){
        if(isprime(i)){
            cout<< i<< " ";
        }
    }
    return 0;
}

// T.C = O(N^2)
// S.C = O(1)

```