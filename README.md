# cplu2.0-string-getline
getting fullname
==================================

#include <iostream>
using namespace std;
int main()
{
    string fullName;
    cout<<" Type your full name: ";
    getline(cin,fullname);
    cout<<" Your name is "<<fullName;
    return 0;
}
  /*output:
  
  Type your full name: Iren Salazar
  Your name is Iren Salazar */
