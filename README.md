using System;
 
class Program
{
    static void Main(string[] args)
    {
        Console.WriteLine("Enter your name:");
        string name = Console.ReadLine();
        Console.WriteLine("Enter your saying:");
        string saying = Console.ReadLine();
 
        DisplayMessage(name, saying);
    }
    static void DisplayMessage(string name, string saying)
    {
        string border = "<><><><><><><><>";
        Console.WriteLine(border);
        Console.WriteLine($"Name: {name}");
        Console.WriteLine($"Saying: {saying}");
        Console.WriteLine(border);
    }
}
