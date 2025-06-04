#include <iostream>
#include <stack>
#include <string>
using namespace std;
int main(){
	stack<int> pila;
	
	pila.push(10);
	pila.push(20);
	pila.push(30);
		
	cout<<"primer elemento "<<pila.top()<<endl;
	
	pila.pop();
	
	cout<<"despues de eliminar, la cima es "<<pila.top()<<endl;
	
	pila.pop();
	
	cout<<"despues sde eliminar, la cima es "<<pila.top()<<endl;
	
	pila.empty();
	
	cout<<"la pila esta vacia "<<pila.empty();


	return 0;
}
