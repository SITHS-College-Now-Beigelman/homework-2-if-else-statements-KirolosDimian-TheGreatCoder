// Kirolos Dimian
// HW 2
// 10/1/24

#include <iostream>
#include <iomanip>
#include <string>

using namespace std;

int main() // This is the function "main"
{
    // Declares the Variables
    double Month_Num;
    double Day_Num;

    // Printing question and guidelines with their input at the end
    cout << "Please input the number of the month and day with a space inbetween (Ex. 3 22 for March 22): " << endl;
    cout << "PLEASE INPUT A REAL MONTH AND A REAL DAY" << endl;
    cin >> Month_Num >> Day_Num;


    // Statements being made for WINTER
    // If statement being made for the months of Jan and Feb since they are entierly in winter
    if (Month_Num == 1 || Month_Num == 2)
    {
        cout << "It is winter!" << endl;
    }

    // If statement being made for the month of Dec, made only for the days 22-31 since they are the only ones in the month that are winter
    if (Month_Num == 12)
    {
        if (Day_Num >= 22 && Day_Num <= 31)
        {
            cout << "It is winter!" << endl;
        }
    }

    // If statement being made for the month of Mar, made only for the days 1-22 since they are the only ones in the month that are in  winter
    if (Month_Num == 3)
    {
        if (Day_Num >= 1 && Day_Num <= 20)
        {
            cout << "It is winter!" << endl;
        }
    }


    // Statements being made in SPRING
    // If statement being made for the months of Apr and May, since they are entierly in spring
    if (Month_Num == 4 || Month_Num == 5)
    {
        cout << "It is spring!" << endl;
    }

    // If statement being made for the month of Jun, made only for the days 1-20 since they are the only ones in the month that are in spring
    if (Month_Num == 6)
    {
        if (Day_Num >= 1 && Day_Num <= 20)
        {
            cout << "It is spring!" << endl;
        }
    }

    // If statements being made for the month of Mar, made only for the days 21-31 since they are the only ones in the month that are in spring 
    if (Month_Num == 3)
    {
        if (Day_Num >= 21 && Day_Num <= 31)
        {
            cout << "It is spring!" << endl;
        }
    }


    // Statements being made in SUMMER
    // If statements being made for the months of Jul and Aug, since they are entierly in the summer
    if (Month_Num == 7 || Month_Num == 8)
    {
        cout << "It is summer!" << endl;
    }

    // If statements being made for the month of Sep, made only for the days 1-22 since they are the only ones in the month that are in the summer
    if (Month_Num == 9)
    {
        if (Day_Num >= 1 && Day_Num <= 22)
        {
            cout << "It is summer!" << endl;
        }
    }

    // If statement being made for the month of Jun, made only for the days 21-31 since they are the only ones in the month that are made in the summer
    if (Month_Num == 6)
    {
        if (Day_Num >= 21 && Day_Num <= 30)
        {
            cout << "It is summer!" << endl;
        }
    }

    // Statements being made in FALL
    //If statement being made for the months of Oct and Nov, since they are entierly in the fall
    if (Month_Num == 10 || Month_Num == 11)
    {
        cout << "It is fall!" << endl;
    }

    // If statement being made for the month of Dec, made only for the days 1-21 since they are the only ones in the month that are in the fall
    if (Month_Num == 12)
    {
        if (Day_Num >= 1 && Day_Num <= 21)
        {
            cout << "It is fall!" << endl;
        }
    }

    // If statement being made for the month of Sep, made only for the days 23-30 since they are the only ones in the month that are in the fall
    if (Month_Num == 9)
    {
        if (Day_Num >= 23 && Day_Num <= 30)
        {
            cout << "It is fall!" << endl;
        }
    }


    // Made to break/end the code
    return 0;
}

/* Output of my code 

Please input the number of the month and day with a space inbetween (Ex. 3 22 for March 22): 
PLEASE INPUT A REAL MONTH AND A REAL DAY
1 12
It is winter!

*/