//# DZ_Seminar2

// Задача 10.
// Напишите программу, которая принимает на вход трехзначное число и на выходе показывает вторую цифру этого числа.
// 456 -> 5
// 782 -> 8
// 918 ->1

// string? imputNumber = Console.ReadLine(); // "456"
// Console.WriteLine($"{imputNumber[1]}");

// Задача 13
// Напишите программу, которая выводит третью цифру заданного числа или сообщает, что третьей цифры нет.
// 645 -> 5
// 78 -> третьей цифры нет
// 32679 -> 6

// Console.Write("Введи число: ");
// int Number = Convert.ToInt32(Console.ReadLine());
// string NumberText = Convert.ToString(Number);
// if (NumberText.Length > 2)
// {
//   Console.WriteLine("третья цифра -> " + NumberText[2]);
// }
// else Console.WriteLine("-> третьей цифры нет");

// Задача 15.
// Напишите программу, которая принимает на вход цифру, обозначающую день недели, и проверяет, является ли этот день выходным.
// 6 -> да
// 7 -> да
// 1 -> нет

// Console.Write("Введи цифру, обозначающую день недели: ");
// int dayNumber = Convert.ToInt32(Console.ReadLine());
//   if (dayNumber == 6 || dayNumber == 7) 
//   {
//   Console.WriteLine("(этот день выходной) -> да");
//   }
//   else if (dayNumber < 1 || dayNumber > 7) 
//   {
//     Console.WriteLine("это вообще не день недели");
//   }
//   else Console.WriteLine("(этот день выходной) -> нет");
