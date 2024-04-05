First-Repository
pyramid Star Pattern Code:
<br>

#include<iostream>
using namespace std;
int main()
{
    int n,i,j,k;
    cout<<"enter the n:";
    cin>>n;
    for(i=1;i<=n;i++)
    {
      for(j=1;j<=n;j++)
      {
        if(j<=n-i)
        {
          cout<<" ";
        }else{
          cout<<i<<" ";
        }
      }cout<<endl;
      
    
    }return(0);
}
