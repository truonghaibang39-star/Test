#include<bits/stdc++.h>
using namespace std;

int main(){
	string S;
	getline(cin, S); 
	sort(S.begin(),S.end(),greater<char>());
	cout<<S;
	return 0;
}
