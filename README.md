using System;
namespace ControlFlowDemo
 {
 class program
{
     static void Main(string[] args)
    {
        int a=1;
        while(a<=8)
        {
            int b=1;
            while(b<=8)
            {
                Console.Write(b+" ");
                b++;
            }
            Console.WriteLine();
            a++;
        }
            Console.ReadKey();
        }
     }
 
       } 
