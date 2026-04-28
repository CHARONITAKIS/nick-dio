#include <stdlib.h>
#include <ctime>
#include <iostream>
srand(time(0)) ;
int dmg = rand() % 26 + 10 ;

using namespace std;



class fighter {
    public:
    string name;
    int health= 100;
    void attack() {
        dmg = rand() % 26 + 10 ;  // dmg dealt method

    }
};

int main() {
    fighter f1;  //fighter 1
    fighter f2; // fighter 2
    f1.health = 100;
    f2.health = 100;
   cout << "name fighter1 : " << f1.name << endl;
    cout << "name fighter2 : " << f2.name << endl;

}


