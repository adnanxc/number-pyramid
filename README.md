# number-pyramid

#include <iostream>
using namespace std;


int main(){
    int rows;

    cout << "Enter number of rows: ";
    cin >> rows;
    int t = rows;

    for(int i=1; i<=rows; i++){
        for(int k=t; k>=0; k--){
            cout << " ";
        }
        for(int j=1; j<=i; j++){
            cout << i << " ";
        }
        t--;
        cout << endl;
    }

}
