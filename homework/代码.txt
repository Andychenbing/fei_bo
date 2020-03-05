#include<iostream>
using namespace std;
class  Fibonacci
{
public:
	int of(int n)
	{
		double gold = (1 + sqrt(5)) / 2;
		return (int)round(pow(gold, n) / sqrt(5));
	}
};


int main()
{
	Fibonacci Fibonacci;
	int N = 1;
	while(N<=200)
	{
		cout << Fibonacci.of(N) << ' ';
		N++;
	}
	system("pause");
}