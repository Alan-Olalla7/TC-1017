//# TC-1017
With great code comes great responsibility//
#include <iostream>
using namespace std;
void newLine ()
{
cout << endl;
}
void threeLine ()
{
newLine (); newLine (); newLine ();
}
void nineLine ()
{
threeLine (); threeLine (); threeLine ();	
}
int main ()
{
cout << "First Line." << endl;
nineLine ();
nineLine ();
nineLine ();
cout << "Second Line." << endl;
return 0;
}
