// Example program
#include <iostream>
#include <string>

using namespace std;

int main()
{

    double price;
    double insertedMoney;
    double change;
    
    cout << "Pleace insert price" << endl;
    cin >> price; 
    cout << "Pleace insert money you gave" << endl;
    cin >> insertedMoney; 
    
    if(price <= insertedMoney)
    {    
        change = insertedMoney - price; 
        cout << "You will get following money" << endl;
        while(change >= 50)
        {
            change -= 50;
            cout << "50 note"<<endl;
        }
        while(change >= 20)
        {
            change -= 20;
            cout << "20 note"<<endl;
        }
        while(change >= 10)
        {
            change -= 10;
            cout << "10 note"<<endl;
        }
        while(change >= 5)
        {
            change -= 5;
            cout << "5 note"<<endl;
        }
        while(change >= 2)
        {
            change -= 2;
            cout << "2 coin/note"<<endl;
        }
        while(change >= 1)
        {
            change -= 1;
            cout << "1 coin"<<endl;
        }
        while(change >= 0.50)
        {
            change -= 0.50;
            cout << "0.50 coin"<<endl;
        }
        while(change >= 0.20)
        {
            change -= 0.20;
            cout << "0.20 coin"<<endl;
        }
        while(change >= 0.10)
        {
            change -= 0.10;
            cout << "0.10 coin"<<endl;
        }
        while(change >= 0.05)
        {
            change -= 0.05;
            cout << "0.05 coins"<<endl;
        }
    }
    else
    {
        cout <<"Money you gave are not enought"<< endl;
    }
    return 0;
}
