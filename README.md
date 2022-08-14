# task2
Ejercicios tema 4

En este ejercicio practicarás las estructuras de control, para ello deberás crear:

Usando un *if, crear una condición que compare si la variable numeroIf es positivo, negativo, o 0.
Pista: Los números inferiores a 0 son negativos y los superiores, positivos.

    public class Main {
    public static void main (String[] args){
        int numeroIf = 0; // variando el cero en un numero positivo o en negativo, la respuesta cambiara//
        if (numeroIf > 0 )
        {
            System.out.println("numeroIf es positivo");
        }
        else if (numeroIf < 0) {
            System.out.println("numeroIf es negativo");
        }
        else{
            System.out.println("numeroIf es igual a 0");
        }
    }
    }

Crea un bucle *While, este bucle tendrá que tener como condición que la variable numeroWhile sea inferior a 3, 
el bloque de código que tendrá el bucle deberá:

Incrementar el valor de la variable en uno cada vez que se ejecute.

Mostrarlo por pantalla cada vez que se ejecute.

    public class Main {
    public static void main (String[] args) {
        int numeroWhile = -4;

    while (numeroWhile < 1) {
        System.out.println(numeroWhile);
        numeroWhile = numeroWhile + 1;
     }
     }
     }
Para el bucle *Do While, deberás crear la misma estructura que en el While, pero solo se debe ejecutar una vez.

    public class Main {
    public static void main (String[] args) {
        int numeroWhile = -4;

    do {
        System.out.println(numeroWhile);
        numeroWhile = numeroWhile + 1;
    } while (numeroWhile < -3);
    }
    }

Para el bucle *For, crea una variable numeroFor, esta variable tendrá como valor 0 y su condición será que la 
variable sea igual o menor que 3, se irá incrementando en 1 su valor cada vez que se ejecute y deberá mostrarse por pantalla.

    public class Main {
    public static void main (String[] args) {
        for (int numeroFor = 0; numeroFor <=3; numeroFor = numeroFor + 1){
            System.out.println(numeroFor);
            }

         }
        }

Por último, para el *Switch, deberás crear la variable estacion, y distintos case para las cuatro estaciones del año. 
Dependiendo del valor de la variable estacion se deberá mandar un mensaje por consola informando de la estación en la que está.
 También habrá que poner un default para cuando el valor de la variable no sea una estación.

    public class Main {
     public static void main(String[] args) {
        int estacion = 2;
        String NombreEstacion;
        switch (estacion) {
            case 1:
                NombreEstacion = "Primavera";
                break;
            case 2:
                NombreEstacion = "Verano";
                break;
            case 3:
                NombreEstacion = "Otoño";
                break;
            case 4:
                NombreEstacion = "Invierno";
                break;

            default: NombreEstacion = "Estación inválida" ;
                break;
        }
        System.out.println("La estación con número: " + estacion + " corresponde a " + NombreEstacion);
     }
    }


