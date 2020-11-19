# Luiza
Code 
//Տպել, սորտավորել եւ շրջել զանգվածի տարրերը
//using System;
//namespace name
//{
//    class Program
//    {
//        static void Main(string[] args)
//        {
//            int[] n = new int[5] { 1, 4, 2, 3, 5 };
//            Console.WriteLine("Zangvaci Tarrer");
//            foreach (int i in n)
//            {
//                Console.WriteLine(i);
//            }
//            Array.Sort(n);
//            Console.WriteLine("Sortavorvac tarrer");
//            foreach (int i in n)
//            { 
//                Console.WriteLine(i);
//            }
//            Array.Reverse(n);
//            Console.WriteLine("Reverse arvac tarrer");
//            foreach (int i in n)
//            {
//                Console.WriteLine(i);
//            }
//            Console.ReadLine();
//        }
//    }
//}



//Գտնել մուտքագրված թվերից, որն է ամենամեծը
//using System;
//using System.Linq;
//using System.Text;

//namespace name
//{
//    class Program
//    {
//        static void Main()
//        {
//            int i = 0;
//            int n = 0;
//            int[] arr = new int[5];
//            Console.WriteLine("Mutqagrir cankacats 5 tiv");
//            for (i = 0; i < arr.Length; i++)
//            {
//                Console.Write("Element[" + (i + 1) + "] =");
//                arr[i] = int.Parse(Console.ReadLine());
//            }
//            n = arr[0];
//            for (i = 1; i < arr.Length; i++)
//            {
//                if (n < arr[i])
//                    n = arr[i];
//            }
//            Console.WriteLine("amenamec tivy = " + n);
//        }
//    }
//}

//jagged array
using System;

namespace name
{
    class Program
    {
        static void Main(string[] args)
        {
            int[][] n = new int[][]
            {
                new int[] { 1, 2 },
                new int[] { 1, 2, 3 },
                new int[] { 1, 2, 3, 4 }
            };
            foreach (int[] i in n)
            {
                foreach (int j in i)
                {
                    Console.Write(j);
                }
            }
        }
    }
}

//Իրար միացնել տարրերը օգտվելով join mrthod-ից
//using System;
//class Program

//{
//    static void Main()

//    {
//        string[] n = new string[5];
//        n[0] = "My";
//        n[1] = "name";
//        n[2] = "is";
//        n[3] = "Luiza";
//        n[4] = "Mkrtchyan";
//        Console.WriteLine(string.Join(" ", n));
//        Console.ReadLine();

//    }
//}

//Գտնել զանգվածի տարրերի գումարը, ամենամեծը եւ ամենափոքրը
//using System;
//using System.Linq;

//namespace name
//{
//    class Program
//    {
//        static void Main(string[] args)
//        {
//            int[] n = { 5, 1, 8, 9 };
//            Console.WriteLine(n.Max()); 
//            Console.WriteLine(n.Min());  
//            Console.WriteLine(n.Sum()); 
//        }
//    }
//}
