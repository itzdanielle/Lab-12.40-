# Lab-12.40-
#include <iostream>
using namespace std;

int main() {
  double numSickDays;
	int numBankTellers;
	double total = 0;

	
	cout << "How many tellers worked at Nation's Bank last year?" << endl;
	cin >> numBankTellers;

	for (int teller = 1; teller <= numBankTellers; teller++)
	{
		cout << endl << "How many sick days was teller "
			<< teller << " out for, during the last year ? " << endl;
		cin >> numSickDays;
		total = total + numSickDays;
	}

	cout << endl;
	cout << "The " << numBankTellers << " tellers were out sick for a total of " << total << " days during the last year" << endl << endl;
}
