# Ejercicio-tema3
//primera parte

package com.open_bootcamp;

public class Main {

    public static void main(String[] args) {
        int resultado = 0;
        resultado = suma(5,10,20);
        System.out.println(resultado);
    }

    public static int suma(int a, int b, int c){
       return a + b + c;
    }
}

//segunda parte

package com.open_bootcamp;

public class Main {

    public static void main(String[] args) {
       Coche miCoche = new Coche();
       miCoche.AgregarPuerta();
       System.out.println(miCoche.puertas);
    }

}
class Coche {
    public int puertas = 4;

    public void AgregarPuerta() {
        this.puertas++;
    }
}
