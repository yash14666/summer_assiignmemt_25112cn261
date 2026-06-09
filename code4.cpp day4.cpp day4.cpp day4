#include <iostream>
#include <cmath>
using namespace std;

int main() {
    int start, end;

    cout << "Enter range: ";
    cin >> start >> end;

    for (int num = start; num <= end; num++) {
        int originalNum = num;
        int digits = 0, result = 0;

        int temp = num;

        // Count digits
        while (temp != 0) {
            digits++;
            temp /= 10;
        }

        temp = num;

        // Calculate Armstrong sum
        while (temp != 0) {
            int rem = temp % 10;
            result += pow(rem, digits);
            temp /= 10;
        }

        if (result == originalNum)
            cout << originalNum << " ";
    }

    return 0;
}