## [Armstrong Number in a Range](https://prepinsta.com/cpp-program/cpp-program-to-find-armstrong-numbers-between-two-intervals/)


```cpp
#include<bits/stdc++.h>
using namespace std;

int Countdigits(int n){
    int count = 0;
    if(n == 0){
        return 1;
    }
    while(n!=0){
        n = n/10;
        count++;
    }
    return count;
}

bool solve(int n){
    int  sum, remain, temp;
   sum = 0;
    temp = n;
    int count = Countdigits(n);
    while(temp>0){
        remain = temp % 10;
         int power = 1;
        for (int i = 0; i < count; i++) {
            power *= remain;
        }
        sum = sum + power;
        temp = temp / 10;
    }
    if(n == sum){
        return true;
    }
    else{
        return false;
    }

}

int main(){
int low, high;
low = 100;
high = 400;

for(int i=100; i<400; i++){
   if(solve(i)){
    cout<< i<<" "<<endl;
   }
}
    return 0;
}

// T.C = O(log10(n))
// S.C = O(1)

```## [Armstrong Number in a Range](https://prepinsta.com/cpp-program/cpp-program-to-find-armstrong-numbers-between-two-intervals/)


```cpp
#include<bits/stdc++.h>
using namespace std;

int Countdigits(int n){
    int count = 0;
    if(n == 0){
        return 1;
    }
    while(n!=0){
        n = n/10;
        count++;
    }
    return count;
}

bool solve(int n){
    int  sum, remain, temp;
   sum = 0;
    temp = n;
    int count = Countdigits(n);
    while(temp>0){
        remain = temp % 10;
         int power = 1;
        for (int i = 0; i < count; i++) {
            power *= remain;
        }
        sum = sum + power;
        temp = temp / 10;
    }
    if(n == sum){
        return true;
    }
    else{
        return false;
    }

}

int main(){
int low, high;
low = 100;
high = 400;

for(int i=100; i<400; i++){
   if(solve(i)){
    cout<< i<<" "<<endl;
   }
}
    return 0;
}

// T.C = O(log10(n))
// S.C = O(1)

```