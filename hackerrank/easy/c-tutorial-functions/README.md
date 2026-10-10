# For Loop

![Difficulty](https://img.shields.io/badge/Difficulty-Easy-green)

## Problem

Functions are a bunch of statements glued together. A function is provided with zero or more arguments, and it executes the statements on it. Based on the return type, it either returns nothing (void) or something.  
<br>
The syntax for a function is

	return_type function_name(arg_type_1 arg_1, arg_type_2 arg_2, ...) {
    	...
        ...
        ...
        [if return_type is non void]
        	return something of type `return_type`;
    }
    
For example, a function to return the sum of four parameters can be written as

	int sum_of_four(int a, int b, int c, int d) {
    	int sum = 0;
        sum += a;
        sum += b;
        sum += c;
        sum += d;
        return sum;
    }

---
Write a function _int max\_of\_four(int a, int b, int c, int d)_ which returns the maximum of the four arguments it receives.  

	+= : Add and assignment operator. It adds the right operand to the left operand and assigns the result to the left operand.
    a += b is equivalent to a = a + b;


**Input Format**

Input will contain four integers - $a, b, c, d$ , one per line.

**Constraints**

 

**Output Format**

Return the greatest of the four integers.
<br>
*PS:* I/O will be automatically handled.

## Solution

**Language:** C++  
**Runtime:** N/A  
**Memory:** N/A  
**Submitted:** 2026-10-10T11:31:46.139Z  

```cpp
#include <iostream>
#include <cstdio>
using namespace std;

int main() {
    int a; 
    int b;
    cin >>a >>b;
    for (int n = a; n<=b; n++ ){
        if (n == 1){
            cout << "one" <<endl;
        }
        else if (n == 2){
            cout << "two"<<endl;
        }
        else if (n == 3){
            cout << "three"<<endl;
        }
        else if (n == 4){
            cout << "four"<<endl;
        }
        else if (n == 5){
            cout << "five"<<endl;
        }
        else if (n == 6){
            cout << "six"<<endl;
        }
        else if (n == 7){
            cout << "seven"<<endl;
        }
        else if (n == 8){
            cout << "eight"<<endl;
        }
        else if (n == 9){
            cout << "nine"<<endl;
        }
        else if (n > 9 && n % 2 == 0) {
            cout <<"even"<<endl;
        }
        else {
            cout << "odd"<<endl;
        }
    }
    return 0;
}


```

---

[View on HackerRank](https://www.hackerrank.com/challenges/c-tutorial-functions/problem)