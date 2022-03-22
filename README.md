# find-the-greatest-number-in-three-number


 using System;

namespace Find_Greatest_Number

{
    class Program
    {
        static void Main(string[] args)
        {
            Console.WriteLine("Find the Largest  Number in three Numbers:\n");
            Console.WriteLine("Enter First Number:\n");
            int a = int.Parse(Console.ReadLine());
            Console.WriteLine("Enter Second Number:\n");
            int b = int.Parse(Console.ReadLine());
            Console.WriteLine("Enter Third Number:\n");
            int c = int.Parse(Console.ReadLine());
            if (a>b && a>c)
            {
                Console.WriteLine("First Number is Greater...");
                if (b>c &&b >a)
                {
                    Console.WriteLine("Second Number is Greater...");
                }
               
            }
            else
            {
                Console.WriteLine("Third Number is Greater...");
            }
            Console.ReadLine();
        }
    }
}
