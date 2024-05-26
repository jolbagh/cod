using System;

class MultiplyByTwo
{
static void Main()
{
Console.Write("enter a number");
int number = Convert.ToInt32(Console.ReadLine());

int result = 2;
for(int i = 0; i < number; i++)
{
result *= 2;
}

Console.WriteLine(result);
}
}
