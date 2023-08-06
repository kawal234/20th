# 20th

#include<iostream>
using namespace std;

// Q1.This is for the factorial of the number
// int f(int n){
//     if(n==1) return 1;
//     int ans = n*f(n-1);
//     return ans;
// }

// int main(){
//     int result = f(5);
//     cout<<result;
//     return 0;
// }

//Q2. fibonacci numbers by recursion

int fib(int n){
    //base case 
    if(n==0 or n==1)  return n;
    return fib(n-1)+fib(n-2);
}

int main(){
    int result = fib(6);
    cout<<result;
    return 0;
}
