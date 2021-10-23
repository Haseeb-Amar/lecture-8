# lecture-8
days of the month
#include <iostream>
using namespace std;
int main()
{
    int month;
    cout << "Enter month number(1-12)";
    cin >> month;

    switch (month)
    {
    case 1:
        printf("31 days");
        break;
    case 2:
        printf("28/29 days");
        break;
    case 3:
        printf("31 days");
        break;
    case 4:
        printf("30 days");
        break;
    case 5:
        printf("31 days");
        break;
    case 6:
        printf("30 days");
        break;
    case 7:
        printf("31 days");
        break;
    case 8:
        printf("31 days");
        break;
    case 9:
        printf("30 days");
        break;
    case 10:
        printf("31 days");
        break;
    case 11:
        printf("30 days");
        break;
    case 12:
        printf("31 days");
        break;
    default:
        printf("Invalid input! Please enter month number between 1-12");
        break;

    }

    return 0;
}
  fuel me up
#include <iostream>
using namespace std;
int main()
{
    cout << " Kindly enter how many litres you want to fill up your car\n ";
    int lit;
    cin >> lit;
    if (lit != 0)
    {
        cout << "You have selected " << lit << " litres\n";
        cout << "Kindly select the fuel type you want for your car\n";
        cout << "Enter 'p' for Petrol\n 'd' for Diesel\n";
        char fuel;
        cin >> fuel;
        switch (fuel)
        {
        case 'P':
        case 'p':
        {

            cout << "You have selected Petrol for filling up your car\n ";
            int a;
            a = lit * 2.4;
            cout << "\nThe price per litres is 2.4 now the total is " << a;
            break;
        }
        case 'd':
        case 'D':
        {
            cout << "You have selected Diesel for filling up your car ";
            int b;
            b = lit * 3.6;
            cout << "\nThe price per litres is 3.6 now the total is " << b;
            break;

            break;
        }

        default:
        {
            cout << "the value does not exists"; break;
        }
        }
    }


}
