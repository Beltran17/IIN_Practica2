# IIN_Practica2
# **Descripción del proyecto**
Los objetivos de este repositorio son:
1. Aprender a usar git de manera más fluida
2. Practicar lo aprendido en clase y ver sus usos 
3. Aprender lo que es un fichero README
# **Pruebas de código**
*Programa de calculadora básica en C#*
`using System;

namespace CalculadoraBasica
{
    class Program
    {
        static void Main(string[] args)
        {
            Console.WriteLine("Calculadora Básica (Suma y Resta)");

            Console.Write("Ingrese el primer número: ");
            double num1 = Convert.ToDouble(Console.ReadLine());

            Console.Write("Ingrese el segundo número: ");
            double num2 = Convert.ToDouble(Console.ReadLine());

            Console.Write("Ingrese  
 la operación (+ o -): ");
            char operacion = Convert.ToChar(Console.ReadLine());

            double resultado;

            switch (operacion)
            {
                case '+':
                    resultado = num1 + num2;
                    break;
                case '-':
                    resultado = num1 - num2;
                    break;
                default:
                    Console.WriteLine("Operación inválida.");
                    return;
            }

            Console.WriteLine("El resultado es: " + resultado);  

        }
    }
}`
---
![captura](screenshot.jpg)
# **Autor**
Beltrán Rodríguez

