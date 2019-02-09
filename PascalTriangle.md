#include <iostream>
using namespace std;

void triangle(int n) {
	for (int line = 1; line <= n; line++) {
		int C = 1;
		for (int i = 1; i <= line; i++) {
			cout << C << " ";
			C = C * (line - i) / i;
		}
		cout << "\n";
	}
}

int main() {
	int n;
	cout << "Input a stage: " << endl;
	cin >> n;
	triangle(n);
	return 0;
}
# week2redo
