# ABC
#include <iostream>
#include <string>
int main() {
	using namespace std;
	setlocale(LC_ALL, "Russian");
	int c = 1;
	do {
		cout << "Введите слово\n";
		string str;
		getline(cin, str);
		int n;
		n = str.length();
		//cout << n << endl;
		for (int i = 0; i < n; i++) {
			if (str[i] == 'a' || str[i] == 'A') {
				cout << "-*";
			}
			if (str[i] == 'b' || str[i] == 'B') {
				cout << "-***";
			}
			if (str[i] == 'c' || str[i] == 'C') {
				cout << "-*-*";
			}
			if (str[i] == 'd' || str[i] == 'D') {
				cout << "-**";
			}
			if (str[i] == 'e' || str[i] == 'E') {
				cout << "*";
			}
			if (str[i] == 'f' || str[i] == 'F') {
				cout << "**-*";
			}
			if (str[i] == 'g' || str[i] == 'G') {
				cout << "--*";
			}
			if (str[i] == 'h' || str[i] == 'H') {
				cout << "****";
			}
			if (str[i] == 'i' || str[i] == 'I') {
				cout << "**";
			}
			if (str[i] == 'j' || str[i] == 'J') {
				cout << "*---";
			}
			if (str[i] == 'k' || str[i] == 'k') {
				cout << "-*-";
			}
			if (str[i] == 'l' || str[i] == 'L') {
				cout << "*-**";
			}
			if (str[i] == 'm' || str[i] == 'M') {
				cout << "--";
			}
			if (str[i] == 'n' || str[i] == 'N') {
				cout << "-*";
			}
			if (str[i] == 'o' || str[i] == 'O') {
				cout << "---";
			}
			if (str[i] == 'p' || str[i] == 'P') {
				cout << "*--*";
			}
			if (str[i] == 'q' || str[i] == 'Q') {
				cout << "--*-";
			}
			if (str[i] == 'r' || str[i] == 'R') {
				cout << "*-*";
			}
			if (str[i] == 's' || str[i] == 'S') {
				cout << "***";
			}
			if (str[i] == 't' || str[i] == 'T') {
				cout << "-";
			}
			if (str[i] == 'u' || str[i] == 'U') {
				cout << "**-";
			}
			if (str[i] == 'v' || str[i] == 'V') {
				cout << "***-";
			}
			if (str[i] == 'w' || str[i] == 'W') {
				cout << "*--";
			}
			if (str[i] == 'x' || str[i] == 'X') {
				cout << "-**-";
			}
			if (str[i] == 'y' || str[i] == 'Y') {
				cout << "-*--";
			}
			if (str[i] == 'z' || str[i] == 'Z') {
				cout << "--**";
			}
			if (str[i] == ' ' || str[i] == ' ') {
				cout << " ";
			}
			
		}
		cout << endl << "Хотите закрыть программу? 1-Да 0-Нет" << endl;
		cin >> c;
		while (c != 1 && c != 0) {
			cout << ("Хотите закрыть программу? 1-Да 0-Нет") << endl;
			cin >> (c);
		}
	} while (c == 0);
	return 0;
}