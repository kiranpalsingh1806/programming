## Coding Examples

### You can also run code and see output yourself!!!   
### Click on 'Code' button on every example to run the code in online compiler

##### Lambda Function [Code](https://onecompiler.com/cpp/3y69t8fda)  
```cpp
#include <bits/stdc++.h>
using namespace std;

int main() 
{
    auto sum = [&](vector<int> &A) {
      int sum = 0;
      for(auto a : A) {
        sum += a;
      }
      
      return sum;
    };
    
    auto doubleElement = [&](vector<int> &A) {
      for(auto &a : A) {
        a = 2 * a;
      }
      return A;
    };
    
    vector<int> V = { 1, 2, 3, 4, 5 };
    int result = sum(V);
    cout << result << "\n";
    
    auto doubleResult = doubleElement(V);
    for(auto n : doubleResult) {
      cout << n << " ";
    }
    cout << "\n";
    
    return 0;
}
```

##### Bitwise Operators [Code](https://onecompiler.com/cpp/3y7gzn3ww)
```cpp
#include <bits/stdc++.h>
using namespace std;

int main() 
{
    bool wanting = true;
    bool police_case = true;
    bool drivingLicence = true;
    bool valid_age = true;
    bool mad = false;
    
    if(wanting || police_case) {
      cout << "You are under arrest" << "\n";
    } else if(drivingLicence && valid_age && !mad) {
      cout << "Yay !!! You can drive" << "\n";
    } else {
      cout << "You cannot drive, dude !!" << "\n";
    }
}
```