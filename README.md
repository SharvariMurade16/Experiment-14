# Experiment-14
## AIM-
To learn about recursion in c++.

### Problem Statement

1.) Write a c++ program to get factorial of a number using recursion.

2.) Write a c++ program to find fibonacci number in the fibonacci sequence using recursion.

3.) Write a c++ program to find sum of n natural numbers using recursion.
### THEORY-
Recursion is a method where a function solves a problem by calling itself to handle smaller, similar tasks. This technique simplifies complex issues by dividing them into easier, more manageable components.

While recursion can be difficult to understand at first, practicing with recursive functions and grasping their base and recursive cases will help clarify how they work and how to effectively use them in problem-solving.
## Code-
#### Factorial-
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
#### Natural sum-
```javascript

//sharvari murade
//23070123088
# include<iostream>
using namespace std;
int sum(int n)
{
    if(n==0)
    {
        cout<< " Number should be greater than 1"<<endl;
    }
    if(n==1)
    {
        return 1;
    }
    else
    {
     return (n+sum(n-1));

    }
}
    int main()
{
    int f,n;
    cout << "Enter a number : "<<endl;
    cin >> n ;

    cout <<"Sum of numbers from 1 to "<<n<<" is: "<<" : "<<sum(n) ;
 
}
```
#### Fibonacci-
```javascript
//Sharvari Murade
//23070123088
#include<iostream>
using namespace std;
int fib(int n)
{
    if(n==0)
    {
        return 0;
    }
    if(n==1)
    {
        return 1;
    }
    else
    {
     return (fib(n-1) + fib(n-2));
    }

}
int main()
{
    int f,n;
    cout << "Enter number of elements: "<<endl;
    cin >> n ;

    cout << n <<"th Fibonacci number in Fibonacci sequence is: "<<fib(n) ;
 
}
```

## Output-
FACTORIAL-
<img width="323" alt="image" src="https://github.com/user-attachments/assets/d80b0314-acf6-496d-a30b-042818b6092a">

NATURAL SUM-
![image](https://github.com/user-attachments/assets/a8f024e1-e0b2-4ccc-8f8e-d9e4415aa132)

FIBONACCI-
![image](https://github.com/user-attachments/assets/859db2d8-0068-4072-9eab-86a82664bbec)





## Conclusion-
Recursion is an effective method for addressing complex problems by breaking them into simpler, smaller sub-problems through a self-calling function. Although it can be difficult to grasp at first, exploring recursive functions and understanding their base and recursive cases will improve your understanding and demonstrate its usefulness in solving diverse problems.




