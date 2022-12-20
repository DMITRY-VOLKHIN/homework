//# homework test
Console.WriteLine("Введите число A: ");
int numberA = int.Parse (Console.ReadLine());
Console.WriteLine("Введите число B: ");
int numberB = int.Parse (Console.ReadLine());

if (numberA > numberB)
{
    Console.WriteLine($"Первое число {numberA} больше чем второе {numberB}"); 
}
else
{
    Console.WriteLine($"Второе число {numberB} больше чем первое {numberA}");
}