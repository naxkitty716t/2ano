using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace nax
{
    internal class Program
    {
        static void Main(string[] args)
        {
            Funcionario f1 = new Funcionario();
            Funcionario f2 = new Funcionario();


            Console.WriteLine("Dados do primeiro funcionario:");
            Console.WriteLine("Nome :");
            f1.nome=Console.ReadLine();
            Console.WriteLine("Salario: ");
            f1.salario = double.Parse(Console.ReadLine());

            Console.WriteLine("Dados do segundo funcionario:");
            Console.WriteLine("Nome :");
            f2.nome = Console.ReadLine();
            Console.WriteLine("Salario: ");
            f2.salario = double.Parse(Console.ReadLine());
            
            double salariomedia = (f1.salario + f2.salario) /2.0;
            Console.WriteLine("salario medio = " + salariomedia);


        }
    }
}
