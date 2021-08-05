#include<bits/stdc++.h>
using namespace std;
int main(){
int t;
cin>>t;
while (t--)
{
    int s;
    cin>>s;
    int a=0,b=0;
    string arr[s];
    for (int  i = 0; i < s; i++)
    {
        cin>>arr[i];
    }
   for (int  i = 0; i < s; i++)
   {
       if(arr[i]=="cookie"&& arr[i+1]=="milk"){
           a++;
       }
        if(arr[i]=="cookie"){
           b++;
       }
   }
   if (a==b)
   {
       cout<<"YES"<<endl;
   }
   else
   {
       cout<<"NO"<<endl;
   }
}
}
   
   
