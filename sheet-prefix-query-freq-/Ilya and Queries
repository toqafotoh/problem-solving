#include <bits/stdc++.h>
#include <iostream>
using namespace std;
typedef long long ll;
const int yayaya = 5e5+5;
int fre[yayaya];
//1e6 means 10 to the power 6
 
int main()
{
  string s; cin >>s;
  int prefix[s.size()];prefix[0]=0;
  for(int i=1;i<s.size();i++){
    if(s[i]==s[i-1])
        prefix[i]=prefix[i-1]+1;
    else
        prefix[i]=prefix[i-1];
  }
  ll t,l,r; cin>> t;
  while(t--){
    cin >> l>>r;
    cout << prefix[r-1]-prefix[l-1]<<endl;
  }
  return 0;
}
