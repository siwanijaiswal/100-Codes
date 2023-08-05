## [Armstrong Number](https://prepinsta.com/cpp-program/to-check-whether-a-number-is-armstrong-number-or-not/)


```cpp
#include<bits/stdc++.h>
using namespace std;

// finding no. of digits in a number
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


void solve(int n){
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
        cout<< "It is armstrong number"<<endl;
    }
    else{
        cout<< "It is not armstrong number"<<endl;
    }

}
// T.C = O(log10(n))
// S.C = O(1)

int main(){
int n;
cin>>n;

solve(n);
    return 0;
}

```## [Armstrong Number](https://prepinsta.com/cpp-program/to-check-whether-a-number-is-armstrong-number-or-not/)


```cpp
#include<bits/stdc++.h>
using namespace std;

// finding no. of digits in a number
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


void solve(int n){
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
        cout<< "It is armstrong number"<<endl;
    }
    else{
        cout<< "It is not armstrong number"<<endl;
    }

}
// T.C = O(log10(n))
// S.C = O(1)

int main(){
int n;
cin>>n;

solve(n);
    return 0;
}

```