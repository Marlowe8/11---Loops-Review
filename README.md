# 11---Loops-Review
//Execute this code and see what’s the issue
#include <iostream>
using namespace std;
int main(){
	int y;
	cout << "Enter a number you want the table of: " << endl;
	cin >> y;
	
	while (cin.fail())
	{
		cout << "Invalid command enter the number again: " << endl;
		cin.clear();
		cin.ignore();
		cin >> y;
	}
	for (int x = 0; x <= 10; x++)
	{
		cout << y << " x " << x << " = " << y * x << endl;
	}
	return 0;
}

//Write the code in a while loop to give this output
*****
***
*
#include <iostream>
using namespace std;
int main(){
	int i=1;
	int j=1;
	while (i <=5) {
		j = i;
		while (j <= 5) {
			cout << "*";
			j++;
		}
		cout << endl;
		i++;
	}
	return 0;
}

//Write the code in a while loop to give this output
*
**
***
****
*****
#include <iostream>
using namespace std;
int main(){
	int i=5;
	int j=1;
	while (i >=1) {
		j = i;
		while (j <= 5) {
			cout << "*";
			j++;
		}
		cout << endl;
		i--;
	}
	return 0;
}


//Write the code in a while loop to give this output
*****
***
*
*
**
***
****
*****
#include <iostream>
using namespace std;
int main(){
	int i=5;
	int j=1;
	int x = 1;
	int y = 1;
	while (x <= 5) {
		y = x;
		while (y <= 5) {
			cout << "*";
			y++;
		}
		cout << endl;
		x++;
	}
	while (i >=1) {
		j = i;
		while (j <= 5) {
			cout << "*";
			j++;
		}
		cout << endl;
		i--;
	}
	return 0;
}

//Factorial
#include <iostream>
using namespace std;

int main(){
	int user, result =1;
	int i=1;
	cout << "Enter any number beside 0 and below: "; cin >> user;
	if (user == 0) {
		system("cls");
		cout << "Error";
		return 0;
	}
	if (cin.fail()) {
		system("cls");
		cout << "Error";
		return 0;
	}
	while (i <= user) {
		result *= i;
		cout << i << " * ";
		i++;
	}
	cout <<"\nThe factorial of " << user << " is " << result;

	return 0;
}






               
  


                                                 


