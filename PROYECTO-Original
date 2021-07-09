# PROYEEECCTTO
using System;

namespace Proyecto
{
    class Program
    {
        static void Main(string[] args)
        {
            float Altura;
            float Peso;
            float IMC;
            string Linea;

            Console.WriteLine("__________Bienvenidos__________ ");
            Console.WriteLine("Ingresar la altura en Metros: ");
            Linea = Console.ReadLine();
            Altura = float.Parse(Linea);
            Console.Write("Ingrese el peso en Kg: ");
            Linea = Console.ReadLine();
            Peso = float.Parse(Linea);

            IMC = Peso / (Altura * Altura);

            Console.WriteLine("Su IMC es de" + IMC);

            if (IMC < 16)
                Console.WriteLine("-Muy Delgado-");
            else if (IMC < 18.50)
                Console.WriteLine("-Peso Aceptable-");

            else if (IMC < 24.99)
                Console.WriteLine("-Peso Normal-");

            else if (IMC < 30)
                Console.WriteLine("-Sobrepeso u Obesidad-");

            else if (IMC < 40)
                Console.WriteLine("Obesidad Extrema");

                    Console.ReadKey();
                    Console.Clear();



        }
    }
}

