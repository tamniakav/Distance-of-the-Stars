# Distance-of-the-Stars
Just another repository
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace _5.Distance_of_The_Stars
{
    class Program
    {
        static void Main(string[] args)
        {
            decimal nearstStar = 4.22m * 9450000000000;
            decimal centerOfGalaxy = 26000 * 9450000000000;
            decimal milkyWay = 100000 * 9450000000000;
            decimal edgeOfTheObservableUnivers = 46500000000m * 9450000000000;

            Console.WriteLine(nearstStar.ToString("e2"));
            Console.WriteLine(centerOfGalaxy.ToString("e2"));
            Console.WriteLine(milkyWay.ToString("e2"));
            Console.WriteLine(edgeOfTheObservableUnivers.ToString("e2"));
        }
    }
}
