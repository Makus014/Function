# Function


//Hello, goodbye
#include <iostream>
using namespace std;

void hello();
void goodbye();



int main() {

	hello();
	cout << endl;

	goodbye();
	cout << endl;

	
	return 0;
}

void hello() {
	cout << "Hello!" << endl;
	cin.get();
}

void goodbye() {
	cout << "Goodbye" << endl;
}
