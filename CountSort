#include <iostream>
#include <bits/stdc++.h>

using namespace std;
ifstream f("data.in");

int A[101], x, n;
int maximum;

int main()
{
    f>>n;
    for(int i = 1; i<=n; ++i)
    {
        f>>x;
        ++A[x];

        maximum = max(maximum, x);
    }

    for(int i = 0; i<=maximum; ++i)
    {
        if(A[i]>0)
        {
            for(int j = 1; j<=A[i]; ++j)
                cout<<i<<" ";
        }
    }
    return 0;
}
