void nat()
{
    Console.WriteLine("Введите n");
    double n = Convert.ToDouble(Console.ReadLine());
    if (n > 1)
    {
        double S = 0;
        double M = 10 * n + 1;
        for (double i = 11; i <= M; i = i + 10)
            S = S + i;
        Console.WriteLine(S);
    }
    else
    {
        Console.WriteLine("error;");
    }
}
    nat();
