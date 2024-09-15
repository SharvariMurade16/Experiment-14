# Experiment-14
## AIM-
To learn about recursion in c++.

### Problem Statement

1.) Write a c++ program to get factorial of a number using recursion.
### THEORY-
Recursion is a method where a function solves a problem by calling itself to handle smaller, similar tasks. This technique simplifies complex issues by dividing them into easier, more manageable components.

While recursion can be difficult to understand at first, practicing with recursive functions and grasping their base and recursive cases will help clarify how they work and how to effectively use them in problem-solving.
## Code-
```javascript
//sharvari murade
//23070123088
#include<iostream>
using namespace std;

int factorial(int n);
int main() {
    int n;
    cout << "Enter a number: ";
    cin >> n;
    cout << "Factorial of " << n << " = " << factorial(n);
    return 0;
}

int factorial(int n) {
    if(n==0){
        return 1;
    } else{
        return n*factorial(n - 1);
    }
}
```
## Output-
<img width="323" alt="image" src="https://github.com/user-attachments/assets/d80b0314-acf6-496d-a30b-042818b6092a">

## Conclusion-
Recursion is an effective method for addressing complex problems by breaking them into simpler, smaller sub-problems through a self-calling function. Although it can be difficult to grasp at first, exploring recursive functions and understanding their base and recursive cases will improve your understanding and demonstrate its usefulness in solving diverse problems.




