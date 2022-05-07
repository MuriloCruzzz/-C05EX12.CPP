#include <iostream>
#include <iomanip>
#include <cctype>
#include "ecra.h" // biblioteca que o desenvolvedor do sistema
using namespace std;

float R, A, B;

void rotadicao(void);
void rotsubtracao(void);
void rotmultiplicacao(void);
void rotdivisao(void);
void entrada(void);
void saida(void);
void pausa(void);

int main(void)
{
  int OPCAO = 0;
  while (OPCAO != 5)
    {
      cout << setprecision(2);
      cout << setiosflags(ios::right);
      cout << setiosflags(ios::fixed);
      clear();
      position( 1, 1); cout << "--------------------";
      position( 2, 1); cout << "Programa Calculadora";
      position( 3, 1); cout << "   Menu Principal   ";
      position( 4, 1); cout << "--------------------";
      position( 6, 1); cout << "[1] - Adicao";
      position( 7, 1); cout << "[2] - Subtracao";
      position( 8, 1); cout << "[3] - Multiplicacao";
      position( 9, 1); cout << "[4] - Divisao";
      position(10, 1); cout << "[5] - Fim de Programa";
      position(12, 1); cout << "Escolha uma opcao: ";
      cin >> OPCAO;
      cin.ignore(80, '\n');
      if (OPCAO != 5)
        {
          switch (OPCAO)
            {
              case  1: rotadicao();        break;
              case  2: rotsubtracao();     break;
              case  3: rotmultiplicacao(); break;
              case  4: rotdivisao();       break;
            }
        }
    }
  return 0;
}
