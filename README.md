#include <iostream>
#include <conio.h>
#include <stdlib.h>
using namespace std;
 
int main()
{
    char name[50];
    cout << "What is your name???" << endl;
    cin.getline(name, 50);
    cout << "You wake up from sleeping because of how boring your job is, your boss is coming! do you: " << name << ". pretend to work or ignore him?" << endl;
    cout << "\n----------------------Press any key to continue----------------------" << endl;
    _getch();
    return 0;
}
system("cls");
    int choiceOne_Path;
    cout << "# What would you like to do?" << endl;
    cout << "\t >> Enter '1' to work" << endl;
    cout << "\t >> Enter '2' to ignore him" << endl;
    retry:
    cout << "\nEnter your choice: ";
    cin >> choiceOne_Path;
    if(choiceOne_Path == 1)
    {
        cout << "\n!!!----------------------Chapter One: The Beggining----------------------!!!" << endl;
        cout << "\nYou left your phone in the bathroom, you go to get it" << endl;
        cout << "You see a pretty gross man" << endl;
        cout << "# you say hey man" << endl;
    }
    else if(choiceOne_Path == 2)
    {
        cout << "\n!!!----------------------Chapter One: The Beggining----------------------!!!" << endl;
        cout << "\nYou left your phone in the bathroom, you go to get it << endl;
        cout << "You see a pretty gross man" << endl;
        cout << "# you say hey man" << endl;
    }
    else
    {
        cout << "invalid response, Press either '1' or '2'!" << endl;
        goto retry;
    }
 
    cout << "\n----------------------Press any key to continue----------------------" << endl;
    _getch();
 
