# Haunted

#include<bits/stdc++.h>
using namespace std;
int main()
{
int n,m;
cin>>n>>m;
int a[n];
map<int,int>res;
int max1=0;
int v=0;
for(int i=0;i<n;i++)
{
cin>>a[i];
if(res.find(a[i])==res.end())
res[a[i]]=1;
else
res[a[i]]++;
if(i==0)
{
cout<<a[i]<<" "<<res[a[i]]<<endl;
val=arr[i];
max1=res[a[i]];
}

else
{
if(max1==res[a[i]] and a[i]>v)
{
val=arr[i];
}
else if(res[a[i]]>max1)
{
v=arr[i];
max1=res[a[i]];
}
cout<<v<<" "<<max1<<endl;
}
}
}


