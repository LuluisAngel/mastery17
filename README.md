# mastery17
Here's the code
      
      
      //Luis Angel Aguilar Carrillo A01225421
      #include <iostream>
      
      using namespace std;
      
      int main(){
      	int x, a;
      
      	cout << "Introduce un numero" << endl;
      	cin >> x;
      
      	if (x<0){
      		a = 1;
      	}
      
      		else if (x>0) {
      			a = 2;
      		}
      
      			else{
      				a = 3;
      			}
      
      	switch (a){    // es un modo alternativo para condiciones
      		
      		case 1:										// si n = 1, se imprimirá lo siguiente.
      		cout << "El numero es negativo" << endl;
      		break;										// el BREAK, es para terminar con ese case.
      
      		case 2:
      		cout << "El numero es positivo" << endl;
      		break;
      
      		default: 									// es como un ELSE, cuando las demás no se cumplen, 
      		cout << "El numero es CERO" << endl;		// se llega aquí y hace otra acción
      		break;
      	}
      
      	return 0;
      }
