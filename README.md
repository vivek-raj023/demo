# demo
This repository is related to demo of cloning.
#include<iostream>
using namespace std;

int main(){
  int i,j,k;
  int n;
  cin>>n;
  for(i=1;i<=n;i++){
      k=i;
      for(j=1;j<=i;++j){
          cout<<k;
          ++k;
      }
      cout<<endl;
  }
  return 0;
}
