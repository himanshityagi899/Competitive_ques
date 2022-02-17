# Competitive_ques

#include <cmath>
#include <cstdio>
#include <vector>
#include<bits/stdc++.h>
#include <iostream>
#include <algorithm>
using namespace std;


int main() {
    int t;
    cin>>t;
    while(t--){
    /* Enter your code here. Read input from STDIN. Print output to STDOUT */   
    int n;
    cin>>n;
  
   int bits= floor(log2(n))+1;
 
   int c= ((1 << bits) - 1) ^ n;
    int ans=n*c;
    cout<<ans<<endl;}
    return 0;
}
