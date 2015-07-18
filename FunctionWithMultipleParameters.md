# LearnCpp
This is where i put all the code that i have learned

#include <iostream>
#include <string>

using namespace std;

int addNumbers(int x, int y){
    int answer = x + y;
    return answer;
}
int main(){
    //cout is to print the return value of addnumbers.
    cout << addNumbers(4,5);

    return 0;
}
