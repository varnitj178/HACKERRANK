#include <bits/stdc++.h>

using namespace std;
int main(){
	
int  cntdigit=0 ;
int n ;
cin>>n ;
    int divdigit=0;
    int temp=n;
    int  temp1= n ;
    int y,x;

    while(temp!=0){
        cntdigit++;

        temp = temp/10;
    }
    for(int i =0;i<cntdigit;i++)
    {
        y = n%10;
        if (y!=0){
		
       	if (temp1%y==0){
       		divdigit++;
		   }
	}
        n /=10;
    }
    cout<<divdigit<<cntdigit<<temp1;
    return 0;
}
