#include <iostream>
using namespace std;
int r;
double mianji;

class yuan
{
	int r;
public:

	int get_s(int r)
	{
		mianji = 3.14*r*r;
		return mianji;
	}
};
int main()
{
	yuan y1;
	cout << "请输入一个圆的半径";
	cin >> r;
	y1.get_s(r);
	cout << "圆的面积=" << mianji;
	cout << "请输入一个圆的半径";
	cin >> r;
}
