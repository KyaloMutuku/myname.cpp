#include <iostream>
#include <string>
using namespace std;

int main() {
    // User details
    string firstName = "Mathew";
    string lastName = "Kyalo";
    string fullName = firstName + " " + lastName;
    string favoriteMeal = "Ugali";
    string favoriteMovie = "Asylum D";
    string reason = "Learning";

    // Output section
    cout << "===== USER PROFILE =====" << endl;
    cout << "First Name     : " << firstName << endl;
    cout << "Last Name      : " << lastName << endl;
    cout << "Full Name      : " << fullName << endl;
    cout << "Favorite Meal  : " << favoriteMeal << endl;
    cout << "Favorite Movie : " << favoriteMovie << endl;
    cout << "Reason in Class: " << reason << endl;
    cout << "===============================" << endl;

    return 0;
}
