#include<iostream> 
#include<cmath>
using namespace std;
int main()
{
float AE, ExactX, ApproximateX;
cout<<"ExactX";
cin>>ExactX;
cout<<"ApproximateX";
cin>>ApproximateX;
AE=fabs(ExactX-ApproximateX);
cout<<AE;
return 0;
}
