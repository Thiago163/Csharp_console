using System;

namespace calculadora
{
    internal class Program
    {
        static void Main(string[] args)
        {
            Console.Beep();
            Console.BackgroundColor = ConsoleColor.Red; 
            Console.ForegroundColor = ConsoleColor.Cyan;

            Console.WriteLine("Digite um Número");
            int num1 = Convert.ToInt32(Console.ReadLine());

            Console.WriteLine("Digite a operação (+, -, *, /)");
            char operacao = Convert.ToChar(Console.ReadLine());

            Console.WriteLine("Digite outro Número");
            int num2 = Convert.ToInt32(Console.ReadLine());

            int result = 0;

            switch (operacao)
            {
                case '+':
                    result = sum(num1, num2);
                    break;
                case '-':
                    result = minu(num1, num2);
                    break;
                case '*':
                    result = mult(num1, num2);
                    break;
                case '/':
                    if (num2 != 0)
                    {
                        result = div(num1, num2);
                    }
                    else
                    {
                        Console.WriteLine("Não é possível dividir por zero.");
                        return;
                    }
                    break;
                default:
                    Console.WriteLine("Operação inválida.");
                    return;
            }

            Console.WriteLine("O resultado é: " + result);
            Console.ReadLine();
        }

        static int sum(int num1, int num2)
        {
            return num1 + num2;
        }

        static int minu(int num1, int num2)
        {
            return num1 - num2;
        }

        static int mult(int num1, int num2)
        {
            return num1 * num2;
        }

        static int div(int num1, int num2)
        {
            return num1 / num2;
        }
    }
}
