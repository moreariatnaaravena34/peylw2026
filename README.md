#include<iostream>
using namespace std;
int main(){
    int alumno, edad=0, altura=0;
    float promedioEdad, promedioAltura, cantidadAlumn=0;
    for( int i=0; i<=5; i++){
        cout<<"ingrese la edad del alumno";
        cin>>edad;
        edad++;
        cout<<"ingrese la altura del alumno";
        cin>>altura;
        altura++;
if(edad>=18){
cantidadAlumn++;
}
promedioAltura=altura/i;
promedioEdad=edad/i;
    }
    cout<<"el promedio de la edad de los alumnos es:"<<edad<<endl;
    cout<<"el promedio de la altura de los alumnos es de:"<<altura<<endl;
    cout<<" la cantidad de alumnos mayores de 18 es de:"<<cantidadAlumn<<endl;
}