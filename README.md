# pattern-question-
   *
  ***
 *****
*******
#include<iostream>
using namespace std;
int main(){
    int n;
    cin>>n;
    int i,j,k,l;
    for(i=1;i<=n;i++){
        for(j=1;j<=n-i;j++){     //This will pirnt the space till n-i
            cout<<" ";
        }
        for(k=1;k<=i;k++){       //This will print * till k<=i;
            cout<<"*";
        }
        for(l=1;l<=i-1;l++){     //This will print third pattern
            cout<<"*";
        }
        cout<<endl;
    }
    return 0;
}
