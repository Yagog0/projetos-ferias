#include <iostream>
using namespace std ;
#include <locale>

   int main() {
       int calculadora;
       float n1, n2, resultado ;

       cout << "escolha uma opçao:\n";
       cout << "1 - soma\n";
       cout << "2 - subtraçao\n";
       cout << "3 - multiplicaçao\n";
       cout << "4 - divisao\n";
       cin >> calculadora;

       cout << "insira o primeiro numero";
       cin >>n1 ;
       
       cout << "insira o segundo numero";
       cin >>n2 ;
   

       
switch (calculadora) {// esse
        case 1: { // Soma
            resultado = n1 + n2;
            cout << "Resultado da soma: " << resultado ;
            break;
        }
        case 2: { // Subtração
            resultado = n1 - n2;
            cout << "Resultado da subtracao: " << resultado ;
            break;
        }
        case 3: { // Multiplicação
            resultado = n1 * n2;
            cout << "Resultado da multiplicacao: " << resultado;
            break;
        }
        case 4: { // Divisão
            if (n2 != 0) {
                resultado = n1 / n2;
                cout << "Resultado da divisao: " ;
            } else {
                cout << "Erro: divisao por zero!" ; 
            }
            break;
        }
        case 5: {
            resultado 
        } 

        default: {
            cout << "Opcao invalida!" ;
            break;
}        
    } 

    return 0; 
}
