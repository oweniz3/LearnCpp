# LearnCpp
This is where i put all the code that i have learned


#include <iostream>
#include <string>

using namespace std;

/*
 * The reason why i  made the variable name private was because making it public could mess the program.
 * When i make it private then there is no way for the main function to access the variable which is a problem.
 * So i had to create two functions. void setName was so i could set the variable x. then make name equals to x.
 * Then i made the getName function. Because it was a string the i had to put string instead of void and then return
 * the name to getName.
 */
class variable{
public:
    void setName(string x){
        name = x;
    }
    string getName(){
        return name;
    }

private:
    string name;


};

int main(){
    variable learn;
    learn.setName("hello");
    cout << learn.getName() << endl;


    return 0;
}
