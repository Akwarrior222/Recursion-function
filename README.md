# Recursion-function
Sum of digits using recursion function

// Recursive C++ program to find sum of digits 
// of a number 
#include <bits/stdc++.h> 

using namespace std; 
 
// Function to check sum of digit using recursion 

int sum_of_digit(int n) 
{ 

    if (n == 0) 

    return 0; 

    return (n % 10 + sum_of_digit(n / 10)); 
} 
 
// Driven code 

int main() 
{ 

    int num = 1234; 

    int result = sum_of_digit(num); 

    cout << "Sum of digits in "<< num 

       <<" is "<<result << endl; 

    return 0; 
} 
 
OUTPUT-:


Sum of digits in 1234 is 10
 
