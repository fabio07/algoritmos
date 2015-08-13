#include "stdafx.h"
#include <iostream>
#include "conio.h"
#include "math.h"
#include "stdlib.h"

using namespace std;

void main ()
{float area, promedio, mayor, lado, n1, n2, n3, a, b;
 int opcion;
 do{
	 cout<<"**********MENU**********\n";
	 cout<<"1.- Area del Cuadrado\n";
	 cout<<"2.- Promedio de 3 Numeros\n";
	 cout<<"3.- El Mayor de 2 Numeros\n";
	 cout<<"0.- Salir\n";
	 cout<<"ingrese opcion";
	 cin>>opcion;
	 switch (opcion)
		    {case 1:
				   cout<<"ingresar el valor del lado del cuadrado:\n";
				   cin>> lado;
				   area= lado*lado;
				   cout<<"el area del cuadrado es:"<<area;
				   break;
			case 2:
				   cout<<"ingresar el valor de n1:\n";
				   cin>> n1;
				   cout<<"ingresar el valor de n2:\n";
				   cin>> n2;
				   cout<<"ingresar el valor de n3:\n";
				   cin>> n3;
				   promedio= (n1+n2+n3)/3;
				   cout<<"el promedio de 3 numeros es:"<<promedio;
				   break; 
			case 3:
				   cout<<"ingresar el valor de a :\n";
				   cin>> a;
				   cout<<"ingresar el valor de b :\n";
				   cin>> b;
				   if (a>b)
					  cout<<"el mayor es a";
				   else
					  cout<<"el mayor es b";
				   break; 
			case 0:
				   cout<<"salir";
                   break;
			default:
				   cout<<"error, opcion invalida";
				   break;
	        }
            getch ();
             system ("cls");
   } while (opcion != 0);
 getch ();    
}
