# assignment-23
------------------------------------------------------ ------------------------------------------------------------------------------------------
1
------------------------------------------------------ ------------------------------------------------------------------------------------------
#include<iostream>
using namespace std;
int main()
{
    cout<<"Hello MySirG";
}
------------------------------------------------------ ------------------------------------------------------------------------------------------
                                                        2
  ------------------------------------------------------ ------------------------------------------------------------------------------------------
  #include<iostream>
using namespace std;
int main()
{
    cout<<"Hello"<<endl<<"MySirG";
}
   ------------------------------------------------------ ------------------------------------------------------------------------------------------
                                                                    3
   ------------------------------------------------------ ------------------------------------------------------------------------------------------
  #include<iostream>
using namespace std;
int main()
{
    int a,b;
    cout<<"enter a nuber a and b";
    cin>>a>>b;
    int sum;
    sum=a+b;
    cout<<sum;
}
 ------------------------------------------------------ ------------------------------------------------------------------------------------------
                                                 4
 ------------------------------------------------------ ------------------------------------------------------------------------------------------
  #include<iostream>
using namespace std;
int main()
{
    int r;
    float a;
    cout<<"enter a nuber r";
    cin>>r;
    a=3.14*r*r;;
    cout<<a;
}
    ------------------------------------------------------ ------------------------------------------------------------------------------------------
                                                           5
    ------------------------------------------------------ ------------------------------------------------------------------------------------------
  #include<iostream>
using namespace std;
int main()
{
    int l,b,h;
    float v;
    cout<<"enter length,breath and hight";
    cin>>l>>b>>h;
   v=l*b*h;
    cout<<v;
}
  ------------------------------------------------------ ------------------------------------------------------------------------------------------
                                                                                           6
 ------------------------------------------------------ ------------------------------------------------------------------------------------------
#include<iostream>
using namespace std;
int main()
{
    int l,b,h;
    float v;
    cout<<"enter a nuber";
    cin>>l>>b>>h;
   v=l+b+h;
    cout<<v/3;
}
  ------------------------------------------------------ ------------------------------------------------------------------------------------------
                                                                     7
  ------------------------------------------------------ ------------------------------------------------------------------------------------------
  #include<iostream>
using namespace std;
int main()
{
    int n,s;
    cout<<"enter a nuber";
    cin>>n;
    s=n*n;
    cout<<s;
}
  ------------------------------------------------------ ------------------------------------------------------------------------------------------
                                                                   8
  ------------------------------------------------------ ------------------------------------------------------------------------------------------
  #include<iostream>
using namespace std;
int main()
{
    int n,s;
    cout<<"enter a number";
    cin>>n>>s;
    int c;
    c=n;
    n=s;
    s=c;
    cout<<"n="<<n<<endl<<"s="<<s;
}
   ------------------------------------------------------ ------------------------------------------------------------------------------------------
                                                                  9
   ------------------------------------------------------ ------------------------------------------------------------------------------------------
  #include<iostream>
using namespace std;
int main()
{
    int n,s;
    cout<<"enter a number";
    cin>>n>>s;
    if(n>s)
    cout<<n<<endl;
    else
    cout<<s<<endl;
}
   ------------------------------------------------------ ------------------------------------------------------------------------------------------
                                                          10
   ------------------------------------------------------ ------------------------------------------------------------------------------------------ 
  #include<iostream>
using namespace std;
int main()
{
   int arr[10],sum=0,i;
   cout<<"enter a array";
   for(int i=0;i<10;i++)
   {
           cin>>arr[i];
   }
   for(i=0;i<10;i++)
   {
    sum=sum+arr[i];
   }
   cout<<"sum of array="<<sum<<endl;
}

  
