// // 1. Напишите программу, которая на вход принимает 2 числа и выдает, какое число больше, а какое меньше.
// // a=5; b=5 -> max=7
// // a=2; b=10 -> max=10
// // a=-9; b=-3 -> max=-3

// Console.WriteLine("Введите первое число:");
// int a = Convert.ToInt32(Console.ReadLine());
// Console.WriteLine("Введите второе число:");
// int b = Convert.ToInt32(Console.ReadLine());
// Console.WriteLine(a > b ? "Первое число больше второго" : "Второе число больше первого");
// {
    
// }

// // 2. Напишите программу, которая принимает на вход три числа и выдает максимальное из этих чисел
// // 2,3,7 -> 7
// // 44,5,78 -> 78
// // 22,3,9 -> 22
 
// public class Exercise8  
// {  
//     public static void Main()
// {
//     int num1, num2, num3;
//     Console.Write("\n\n");
//     Console.Write("Find the largest of three numbers:\n");
//     Console.Write("------------------------------------");
//     Console.Write("\n\n");
//     Console.Write("Input the 1st number :");
//     num1 = Convert.ToInt32(Console.ReadLine());
//     Console.Write("Input the  2nd number :");
//     num2 = Convert.ToInt32(Console.ReadLine());
//     Console.Write("Input the 3rd  number :");
//     num3 = Convert.ToInt32(Console.ReadLine());
 
//   if (num1 > num2)
//     {
//         if (num1 > num3)
//         {
//             Console.Write("The 1st Number is the greatest among three. \n\n");
//         }
//         else
//         {
//             Console.Write("The 3rd Number is the greatest among three. \n\n");
//         }
//     }
//     else if (num2 > num3)
//         Console.Write("The 2nd Number is the greatest among three \n\n");
//     else
//         Console.Write("The 3rd Number is the greatest among three \n\n");
// }
// }


// // 3. Напишите программу, которая на вход принимает число и выдает, является ли это число четным (делится на 2 без остатка)
// // 4-> да
// // -3-> нет 
// // 7-> нет 

// Console.WriteLine("Введите число");
// int num = Convert.ToInt32 (Console.ReadLine());
// if(num%2==0)
// Console.WriteLine("Число четное");
// else
// {
//     Console.WriteLine("Число нечетное");
// }

// // 4. Написать программу, которая на входе принимает число (N), а на выходе показывает все четные от 1 до N.
// // 5->2,4
// // 8->2,4,6,8

// Console.WriteLine("Введите число N");
// int num = Convert.ToInt32(Console.ReadLine());
// for(int i=1;i<=num;i++)
// {
// if (i % 2 == 0)
// System.Console.Write(i + ",");
// }
