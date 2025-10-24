#include<iostream>
using namespace std;
void main()
{
	long population;
	double area, density;
	
	cout << "please enter the population of you area" << "\n";
	cin >> population;

	cout << "please enter the area " << "\n";
	cin >> area;

	cout << "the population of the area=" << population << "\n";
	cout << "the area=" << area << "\n";
	density = population / area;
	cout << "density=" << density<<"people per square miles" << "\n";
	
}
