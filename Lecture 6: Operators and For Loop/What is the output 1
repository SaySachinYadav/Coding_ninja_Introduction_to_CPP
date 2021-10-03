#include <iostream>
using namespace std;
int main() 
{    
         int x, y = 1;
         x = 10;
         if (x != 10 && x / 0 == 0)
            cout << y;
         else
             cout << ++y;
} 




Correct Answer: 2



Solution Description
Even though you get the output as '2', you'll also get a "division by zero" warning. The reason you only get a warning but not an error is short-circuit evaluation. 
In the if statement, once the first condition (x != 10) is evaluated to be false, then the second condition (x / 0 == 0) is not even executed because the result 
of the overall condition (x != 10 && x / 0 == 0) will be false. Even if the second condition were true, it would not change the overall result of the two conditions.

However, if the value of x or the first condition itself is changed so that it evaluates to true, then you will get an error because in that case the second 
condition would also be checked (or executed).
