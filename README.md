# While-loop-stars-1-to-5-
rising stars
#include<iostream>
using namespace std;
int main()
{
	int s, k=1;   //declaring variable with datatype integer
	s = 1;   //assigning value to variable 's'
	while (s <= 5)    //using while loop
	{
		k = 1;    //assigning value to variable 'k'
		while (k <= s)    //using while loop
		{
			k++;
			cout << "*";
		}
		s++;
		cout << endl;
	}
	return 0;
}
