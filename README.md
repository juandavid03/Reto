# Reto

using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace ConsoleApplication2
{
        public delegate string zona(string zonas);
        public delegate int impuesto(int total);

    class Program
    {


        public static  string zonas(string zona)
        {
            if (zona == "zona1")
            {
                int precioz1;
                string precio;
                int impuesto;
                Console.WriteLine("ingrese un el precio");
                precio = Console.ReadLine();
                int.TryParse(precio, out impuesto);
                impuesto si = precioz1;
                precioz1 = precio * 25 / 100;
                Console.WriteLine("El impuesto es: {0}", precioz1);
                
            }
            if (zona == "zona2")
            {
                int precioz2;
                string precio;
                int impuesto;
                Console.WriteLine("ingrese un el precio");
                precio = Console.ReadLine();
                int.TryParse(precio, out impuesto);
                impuesto si = precioz2;
                precioz2 = (precio* 12 / 100) + 25;
                Console.WriteLine("El impuesto es: {0}", precioz2);

            }
            if (zona == "zona3")
            {
                int precioz3;
                string precio;
                int impuesto;
                Console.WriteLine("ingrese un el precio");
                precio = Console.ReadLine();
                int.TryParse(precio, out impuesto);
                impuesto si = precioz3;
                precioz3 = precio * 8 / 100;
                Console.WriteLine("El impuesto es: {0}", precioz3);

            }

            if (zona == "zona4")
            {
                int precioz4;
                string precio;
                int impuesto;
                Console.WriteLine("ingrese un el precio");
                precio = Console.ReadLine();
                int.TryParse(precio, out impuesto);
                impuesto si = precioz4;
                precioz4 = (precio * 4 / 100) + 25;
                Console.WriteLine("El impuesto es: {0}", precioz4);

            }
           
          return zona;
                   
        }
        }
    }
