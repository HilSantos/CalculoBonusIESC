# CalculoBonusIfElSiCa
Crie um programa que peça ao usuario seu salario (tipo decimal), e o tempo de serviço na empresa em anos (tipo int). O programa deve calcular um bônus salarial baseado no tempo de serviço:
Menos de 1 ano: Nenhum bônus
Entre 1 e 5 anos: Bônus de 5% do salario
Mais de 5 anos: Bônus de 10% do salario
Use If/Else para aplicar as condições acima. Em seguida, utilize switch case para classificar o bônus:
Se o Bônus for menos que 500 reais: "Bônus pequeno", entre 500 e 1000 reais: "Bônus medio", acima de 1000 reais: "Bônus grande". Exiba o salario final com o bônus e a classificação do
bônus no console.

using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace CalculoBonusIfElseSwitchCase
{
    public class Program
    {
        static void Main(string[] args)
        {
            decimal salario;
            int tempServ, anos;
            string bônus;

            Console.WriteLine("Informe o valor do salario: ");
            salario = decimal.Parse(Console.ReadLine());

            if (anos > 1)
            {
                Console.WriteLine("Nenhum bônus");
            }
            else if (anos == 5)
            {
                Console.WriteLine("Bônus de 5% do salario");
            }
            else (anos > 5)
            {
                Console.WriteLine("Bônus de 10% do salario");
            }

            }


            Console.ReadKey();
        }
    }
}

