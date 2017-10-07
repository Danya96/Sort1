# Sort1

#include <iostream>
#include <vector>
using namespace std;
 
 
int main(){
	int n, m, c;
	cin >> n >> m;
	vector <int> a;
 
	for (int i = 0; i < n; i++) {
		for (int j = 0; j < m; j++) {
			cin >> c;
			a.push_back(c);
		}
 
	}
 
	int x, y;
	cin >> x >> y;
	cout << a[x*m + y];
	return 0;
}
