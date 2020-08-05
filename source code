#include <iostream>
#include <math.h>
#include <stdio.h>
#include <bits/stdc++.h>
using namespace std;

    int main()
    {
        double n,a,b,x;
        double f1=0,f2=0,f3=0;
        cout<<"______BISECTION METHOD (NUMERICAL METHODS)______"<<endl<<endl;
  cout<<"Enter the degree of the polynomial: "<<endl;
  cin>>n;
  printf("-------------------------------------------------------\n");

  int arr[(int)n],j=0;

  for(int i=0;i<=n;i++)
  {
    printf("Enter the coefficient of x^%d: \n ",i);
    cin>>arr[i];
  }
  printf("--------------------------------------------------------\n");
  cout<<"Enter the lower bound and upper bound: "<<endl;
  cin>>a>>b;
  printf("---------------------------------------------------------\n");
  cout<<"Enter the number of iterations: "<<endl;
  int k;
  cin>>k;
  printf("---------------------------------------------------------\n");
  cout<<"Correct to how many decimal places?"<<endl;
  int p;
  cin>>p;
  printf("---------------------------------------------------------\n");
  printf("a\t\tb\t\tx\t\tf(x)\n");
  printf("---------------------------------------------------------\n");
  while(j<k)
  {
    x=(a+b)/2;
    for(float i=0;i<=n;i++)
      {

        f1=f1+arr[(int)i]*pow(a,i);
        f2=f2+arr[(int)i]*pow(b,i);
        f3=f3+arr[(int)i]*pow(x,i);
      }
      printf("%lf\t%lf\t%lf\t%lf\n",a,b,x,f3);
      if((f3)<0)
        {
          a=(a+b)/2;
        }
      else
        {
          b=(a+b)/2;
        }
        f1=0;
        f2=0;
        f3=0;
        j++;
  }
      printf("\n");
      cout<<"ANSWER: "<<endl;
      cout<<fixed<<setprecision(p)<<x<<endl;
      return 0;
}
