using System;

class Program { static void Main() {

    Console.ForegroundColor = ConsoleColor.Red;


    Console.Write("Por favor, escribe tu nombre: ");
    string nombre = Console.ReadLine();


    Console.Write("ingresa tu edad ");
    int edad = Console.ReadLine();

    Console.WriteLine("❤ ¡Hola, " + nombre + edad + "! ❤");


    Console.ResetColor();


    Console.WriteLine("Presiona cualquier tecla para salir...");
    Console.ReadKey();
}
}
