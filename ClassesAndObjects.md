# LearnCpp
This is where i put all the code that i have learned

#include <iostream>
#include <string>

using namespace std;

//A class croups similar functions together.

class Learning{
public:
    void coolsaying(){
        cout << "hello world" << endl;
    }
};



int main(){
    Learning Learnobject;
    Learnobject.coolsaying();

    return 0;
}
