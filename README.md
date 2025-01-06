#include <iostream>
using namespace std;

int main()
{

    int n;
    cout << "Enter the number";
    cin >> n;
    int p = n - 1;

    for (int i = n + 1; i >=1; i--)
    {
        for (int j = 1; j <= 2 * n; j++)
        {
            if ((j == (n + 1 - i)))
            {
                cout << "*";
            }
            else
            {
                cout << " ";
            }

            if (i != 1)
            {
                if (j == (n + i - 2))
                {
                    cout << "*";
                }
            }
        }
        cout << endl;
    }

    // for(int i=n+1; i<=2*n; i++){
    //     for(int j=1; j)
    // }

    return 0;
}
