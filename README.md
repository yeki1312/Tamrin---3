# Tamrin---3using System;

class Program
{
    static void Main()
    {
        int number;
        long product = 1;

        Console.WriteLine("اعداد را وارد کنید (برای پایان 0 وارد کنید):");

        while (true)
        {
            Console.Write("عدد: ");
            number = int.Parse(Console.ReadLine());

            if (number == 0)
                break;

            product *= number;
        }

        Console.WriteLine("حاصل‌ضرب اعداد وارد شده: " + product);
    }
}

