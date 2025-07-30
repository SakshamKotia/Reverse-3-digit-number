#include<iostream>
#include<string>
#include<algorithm>

    using namespace std;
    int solve(int n)
    {
        string s = to_string(n)
        reverse(s.begin(), s.end());
        n = stoi(s);

        return n;
    }
    int main()
    {
        int n;
        cin >> n;
        cout << solve(n) << endl;
        return 0;
    }
