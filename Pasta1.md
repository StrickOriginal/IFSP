#include <iostream>
#include <locale>
using namespace std;

int main()
{
    setlocale(LC_ALL,"portuguese");
    int c = 0, n;
    cout << "Digite um número:" << endl;
    cin >> n;
    if(n != 0);
    do{
    cout << "Digite um número:" << endl;
    cin >> n;
    c = c + 1;
    }while (n != 0);
     cout << "Você digitou " << c << " números.";
    return 0;
}

