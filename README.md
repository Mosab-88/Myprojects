#include<iostream>

using namespace std;



int mos(int w, int u) {

	int s = w*u;
	
	cout << s << endl;

	return s;


}

int bos(int x, int y) {

	int s= x / y;


	cout << "n1" << endl;
	cin >> x;
	cout << "n2" << endl;
	cin >> y;
	//cout << s << endl;


	return s;


}
int cos(int e, int r) {

	int s = e - r;

	cout << "n1" << endl;
	cin >> e;
	cout << "n2" << endl;
	cin >> r;
	//cout << s << endl;
	return s;

}



int main() {
	int a, b;
	cout << "n1"  << endl;
	cin >> a;

	cout << "n2" << endl;
	cin >> b;

	mos(a, b);
	bos(a, b);
	cos(a, b);
	cout << "thanx" << endl;
	






 
	
	




	
	
	system("pause");





}
