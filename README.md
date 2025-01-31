#include <iostream>
using namespase std;
int main() 
{
double x, y, z;
cout << "Enter the first number";
cin>> x;
cout << "Choose an opetation (+, -, *, /)"
cin>> operation;
cout << "Enter the second number";
cin>> y;
switch (operation)
{
case '+';
result = x + y;
case '-';
result = x - y;
case '*';
result = x * y;
case '/';
if(y != 0 )
{
result = x / y;
}
else
{
cout <<"Error";
}
}
return 0;
}
