using System;
using System.Globalization;

namespace atvClasses
{
    class Program
    {
        static void Main(string[] args)
        {
            Produto p1;

            p1 = new Produto();

            Console.WriteLine("Entre com os dados do produto: ");
            Console.Write("Nome: ");
            p1.Nome = Console.ReadLine();
            Console.Write("Preço: ");
            p1.Preco = double.Parse(Console.ReadLine(), CultureInfo.InvariantCulture);
            Console.Write("Quantidade no estoque: ");
            p1.Quantidade = int.Parse(Console.ReadLine());

            Console.WriteLine("Dados do produto: " + p1);
            Console.WriteLine();

            Console.Write("Digite o número de produtos a ser adicionado ao estoque: ");
            int qtd = int.Parse(Console.ReadLine());
            Console.WriteLine();

            p1.AdicionarProdutos(qtd);
            Console.WriteLine("Dados atualizados: " + p1);
            Console.WriteLine();

            Console.Write("Digite o número de produtos a ser removido do estoque: ");
            qtd = int.Parse(Console.ReadLine());
            Console.WriteLine();

            p1.RemoverProdutos(qtd);
            Console.WriteLine("Dados atualizados: " + p1);


            
        }

    }
}
