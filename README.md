Sprew
=====
// Amir Hosseinbor
// Uppgift 6
#include<iostream.h>
#include<conio.h>
#include<iomanip.h>
using namespace std;

int main()
{
    int tal;
    cout<< "Ange ett heltal: ";
    cin>>tal;
    cout<<"Nedraknat: ";
    while (tal>0){
          cout<<tal<<" ";
       tal--;
    } // while
    
    cout<<"\n";
    system("pause");
    return 0;
    
}//Main

    
} //main