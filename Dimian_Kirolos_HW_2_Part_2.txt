// Kirolos Dimian
// HW 2
// 10/3/24

#include <iostream>
#include <string>

using namespace std;



int main() // This is the function "main"
{
    // Declaring Variables
    double Score1;
    double Score2;
    double Score3;
    double Score4;
    double Score5;
    double Score6;

    // Asking and allowing for the user to have an input
    cout << "Please enter the 6 numbers of the 6 scores that were given by the judges. Please press enter after entering each one from 0.0 to 10.0" << endl;
    cin >> Score1;
    cin >> Score2;
    cin >> Score3;
    cin >> Score4;
    cin >> Score5;
    cin >> Score6;

    // Declaring new variables for the maximum and minimum scores that will be used as comparison to each of the scores
    double MaxScore = Score1;
    double MinScore = Score1;

    // Creating if statements for each of the scores to find out the highest and lowest one 
    // FOR ALL: If the MaxScore each time is less than that of the score compared to then that score is the new max score
    // If the MinScore each time is greater than that of the score being compared to then that score is the new min score

    // The if statement being made for Score 2 to find out if it may be the highest/lowest score
    if (MaxScore < Score2)
    {
        MaxScore = Score2;
    }
    if (MinScore > Score2)
    {
        MinScore = Score2;
    }

    // The if statement being made for Score 3 to find out if it may be the highest/lowest score
    if (MaxScore < Score3)
    {
        MaxScore = Score3;
    }
    if (MinScore > Score3)
    {
        MinScore = Score3;
    }

    // The if statement being made for Score 4 to find out if it may be the highest/lowest score
    if (MaxScore < Score4)
    {
        MaxScore = Score4;
    }
    if (MinScore > Score4)
    {
        MinScore = Score4;
    }

    // The if statement being made for Score 5 to find out if it may be the highest/lowest score
    if (MaxScore < Score5)
    {
        MaxScore = Score5;
    }
    if (MinScore > Score5)
    {
        MinScore = Score5;
    }

    // The if statement being made for Score 6 to find out if it may be the highest/lowest score
    if (MaxScore < Score6)
    {
        MaxScore = Score6;
    }
    if (MinScore > Score6)
    {
        MinScore = Score6;
    }

    // Adding all of the scores together under a variable
    double REAL_TotalScore = Score1 + Score2 + Score3 + Score4 + Score5 + Score6;

    // Taking the total and subtracting the maximum and minimum from the total as the problem asks
    double ChangedScore = REAL_TotalScore - (MaxScore + MinScore);

    // Dividing the new, changed score by 4 to find the total score
    double FinalScore = ChangedScore / 4;

    // The print statement for the final score 
    cout << "The final score that is being given to this player is " << FinalScore << endl;

    return 0;
}

/* Output of my code
Please enter the 6 numbers of the 6 scores that were given by the judges. Please press enter after entering each one from 0.0 to 10.0
3.7
5.8
4.2
1.3
0.1
8.4
The final score that is being given to this player is 3.75
*/