# Day 1
#include <iostream>
#include <vector> //khai báo thư viện vector
using namespace std;

int main ()
{
	vector<int> arr; // Cú pháp: vector<KieuDuLieu> TenVecTor;
	for (int i = 0; i < 11; i++) // thêm phần tử vào trong vector
	{
		arr.push_back(i);
	}
	for (int i = 0; i < 11; i++) {
		cout <<"\t" << arr[i];
	}
	int sum = 0;
	for (int i = 0; i < arr.size(); i++) //tính tổng của các phần tử trong vector
	{
		sum += arr[i];
	}
	cout << "\nsum = " << sum << endl;
	system("pause");
	return 0;
}
