#include <iostream>
using namespace std;

int main() {
    // Declaración de variables
    double numero1, numero2, suma, resta, multiplicacion, division;

    // Solicitar al usuario que ingrese los dos valores
    cout << "Introduce el Valor del primer numero: ";
    cin >> numero1;

    cout << "Introduce el Valor del segundo numero: ";
    cin >> numero2;

    // Realizar las operaciones matemáticas
    suma = numero1 + numero2;
    resta = numero1 - numero2;
    multiplicacion = numero1 * numero2;

    // Verificar si el segundo número es distinto de cero para realizar la división
    if (numero2 != 0) {
        division = numero1 / numero2;
    } else {
        // En caso de intentar dividir por cero, mostrar un mensaje de error
        cout << "Error: No se puede dividir por cero." << endl;
        return 1; // Se puede usar un código de retorno no cero para indicar un error
    }

    // Mostrar los resultados en pantalla con sus respectivos enunciados
    cout << "la suma es: " << suma << endl;
    cout << "la Resta es: " << resta << endl;
    cout << "la Multiplicacion es: " << multiplicacion << endl;
    cout << "la division es: " << division << endl;

    return 0;
}
