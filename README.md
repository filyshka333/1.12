#include <iostream>
using namespace std;
class Krab {
 string name;
public:
 void res()
 {
  cout << "Введите ваше имя:  " << name << endl;
  cin >> name;
  cout <<"Привет, "<< name <<"!"<< endl;
 }
};
int main()
{
 setlocale(LC_ALL, "Russian");
 Krab k;
 k.res();
 
}
