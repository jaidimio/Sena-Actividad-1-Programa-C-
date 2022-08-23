# Sena-Actividad-1-Programa-C-
Programa para introducir datos por pantalla
#include <iostream>
using namespace std;

int main ( ) {
	
	int ref_calzado;
	int talla_calzado;
	int costo_calzado;
	int precio_venta;
	char descripcion[50];
	char disponible_venta;

	
	cout <<"Digite la Referencia:  " << endl; 
	cin>> ref_calzado;
	cout <<"Digite la Talla del Zapato:    "<< endl; 
	cin>> talla_calzado;
	cin.ignore(256, '\n');
	cout <<"Digite la Descripcion del calzado:    "<< endl;
	cin.getline(descripcion, 50);
	cout <<"Esta disponible S/N: "<< endl;
	cin >> disponible_venta;
	cout <<"Digite el costo del calzado:  "<< endl;
	cin>> costo_calzado;
	cout <<"Digite el precio de Venta:   "<< endl;
	cin>> precio_venta;
	
	system ("cls");  
	
	cout <<"\nLa Referencia es:" <<ref_calzado<< endl;
	cout <<"\nLa talla del Zapato es:    "<<talla_calzado << endl;
	cout <<"\nLa Descripcion del calzado es:    "<<descripcion << endl;
	cout <<"\nEl costo de venta es:     " <<costo_calzado << endl;
	cout <<"\nEl precio de venta es:     " <<precio_venta << endl;
	
	cout <<"\nGracias por Digitar la Informacion\n" << endl;
	cout <<"\nCodigo desarrollado por Jaidi Gonzalez\n" <<endl;
	system ("pause");
	
	return EXIT_SUCCESS; 
	
	
	}
