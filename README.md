# Radius-of-Circle
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;

namespace ConsoleApplication2
{
    class Program
    {
        static void Main(string[] args)
        {
            float width, height, radius, area_of_rectangle, area_of_circle, area_of_shaded_region;
            Console.WriteLine("Enter the width");
            width = float.Parse(Console.ReadLine());
            Console.WriteLine("Enter the height");
            height = float.Parse(Console.ReadLine());
            area_of_rectangle = height * width;
            Console.WriteLine("Enter the radius of circle");
            radius = float.Parse(Console.ReadLine());
            area_of_circle = 22 / 7 * radius * radius;
            area_of_shaded_region = area_of_rectangle - area_of_circle;
            Console.WriteLine("The area of circle {0}", area_of_circle);
            Console.WriteLine("The area of rectangle {0}", area_of_rectangle);
            Console.WriteLine("The area of shaded region {0}", area_of_shaded_region);
            Console.ReadLine();

        }
    }
}
