# caixaEletronicoCsharp-
Código simples que se assemelha com um caixa eletrônico de banco. 




// se o resto da divisão do saque por x for 0 imprima x mas se x não for 0, divida pelo proximo
// saque%a == 0 Console.WriteLine("{a}",a)
// 
using System;
class saque {
  static void Main() {
 int a, b, c, d, e, saque;
   
    Console.Write("Digite o quanto quer sacar: ");
    saque = int.Parse(Console.ReadLine());
    a = saque / 50;
    saque = saque%50;
    b = saque / 10;
    saque = saque%10;
    c = saque / 5;
    saque = saque%5;
    d = saque / 2;
    saque = saque%2;
    e = saque / 1;
    
    if (a != 0){
        Console.WriteLine("Voce tem {0} notas de 50",a);
    }
    if(b != 0){
        Console.WriteLine("Voce tem {0} notas de 10",b);
    }
    if(c != 0){
        Console.WriteLine("Voce tem {0} notas de 5",c);
    }
    if(d != 0){
        Console.WriteLine("Voce tem {0} notas de 2",d);
    }
    if(e != 0){
        Console.WriteLine("Voce tem {0} notas de 1",e);
    }

  }
}




