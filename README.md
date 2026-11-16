# info-github-csharp
Учебный проект C# для знакомства с GitHup
using System;
class Program
{
static void Main()
{
Console.Write ("Как тебя зовут?");
string name=Console.Deadline()??"";
if(string.IsNullOrWhiteSpace(name))
{
Console.Write ("Имя не введено");
}
else
{
Console.Write ("Привет,"+name+"!");
}
}
}
