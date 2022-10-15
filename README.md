# RUDRA
// C# implementation of the approach
using System;
 
class GFG
{
 
// Function to check if it is possible
// to cut the pizza in the given way
static void cutPizza(int n)
{
    // Case 1
    Console.Write((360 % n == 0) ? "1" : "0");
 
    // Case 2
    Console.Write((n <= 360) ? "1" : "0");
 
    // Case 3
    Console.Write((((n * (n + 1)) / 2) <= 360) ? "1" : "0");
}
 
// Driver code
public static void Main(String []args)
{
    int n = 7;
    cutPizza(n);
}
}
