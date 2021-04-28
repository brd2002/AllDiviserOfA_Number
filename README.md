# AllDiviserOfA_Number
code is implemented in c++;
     #include<iostream>
#include<limits.h>
using namespace std;
void printDivisors(int n)
{
    for(int i = 1;i*i<=n;i++)
    {
        if(n%i==0)
        {
            cout<<i << "  ";
            if(i != (n/i))
                cout<< (n/i)<< "  ";
        }
    }
}
int main()
{
    int n;
    cin>>n;
    printDivisors(n);
    return 0;
}
// code with brdcoder007
