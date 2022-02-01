# Priniting-tables-using-Goto-Statement-in-C++

#include<iostream>
using namespace std;
int main()
{
    int i=1,n,m,a;
    cout<<"Enter the limit :";
    cin>>n;
    cout<<"Enter the table's number :";
    cin>>a;
    start:
        cout<<"\n"<<i<<"*"<<a<<"="<<i*a;
        i++;
        if(i<=n)
        {
            goto start;
        }
    return 0;
}
