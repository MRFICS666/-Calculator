This is code in C#

my first project))

by OneNightGIGIRO_

using System;

namespace ConsoleApplication2
{
    internal class Program
    {
        public static void Main(string[] args)
        {
            Console.WriteLine("Введите первое число");
            int a = Convert.ToInt32(Console.ReadLine());

            Console.WriteLine("Введите второе число");
            int b = Convert.ToInt32(Console.ReadLine());

            Console.WriteLine("Введите нужную операцию ");

            Console.WriteLine("1 - Деление");
            Console.WriteLine("2 - Умножение");
            Console.WriteLine("3 - Вычитание");
            Console.WriteLine("4 - Сложение");
            
            int c = Convert.ToInt32(Console.ReadLine());
            
            int d = 0;

            if (c == 1)
            {
                Console.WriteLine("Вы выбрали деление");
                d = a / b;
                Console.WriteLine("Ответ: " + d);
                
                
            }

            if (c == 2)
            {
                Console.WriteLine("Вы выбрали умножение");
                d = a * b;
                Console.WriteLine("Ответ: " + d);
            }

            if (c == 3)
            {
                Console.WriteLine("Вы выбрали вычитание");
                d = a - b;
                Console.WriteLine("Ответ: " + d);
            }

            if (c == 4)
            {
                
           
            Console.WriteLine("Вы выбрали сложение");
            d = a + b;
            Console.WriteLine("Ответ: " + d);
            } 
        }
    }
}
