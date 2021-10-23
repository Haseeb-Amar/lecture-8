# lecture-8
days of the month excercise 1
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
fuel me up excercise 2
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
switch temp excercise 3
    

#include <iostream>

using namespace std;
int main()
{

	cout << "what temperature you want to convert" << endl;
	cout << "if you want to convert celcius to fahrenheit type 'c'" << endl;
	cout << "if you want to convert fahreheit to celcius type 'f'" << endl;

	char select;
	int temp;
	cin >> select;
	switch (select)
	{
	case 'c':
	case 'C':

	{
		cout << "\nenter the temp to convert from celcius to fahrenheit\n";
		cin >> temp;
		temp = (temp * 1.8) + 32;
		cout << "\n The temperature is " << temp;
		break;
	}
	case 'f':
	case 'F':
	{
		cout << "\nenter the temp to convert from fahrenheit to celcius\n";
		cin >> temp;
		temp = (temp - 32) * 0.5556;
		cout << "\n The temperature is " << temp;
		break;
	}

	default:
	{
		cout << "invalid";
		break;
	}

	}
	return 0;
}


