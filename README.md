# Practica-4---Primer-parcial

Copia el siguiente codigo en tu editor:

1. Cree una funcion que cheque si un numero introducido por el usuario es par o impar.
* Complete las lineas para que el usuario pueda introducir los numero.

Copie el siguiente codigo:

```java
import java.util.Scanner;

public class ParImpar {
    
    public static String verificarParImpar(int num) {
        /* Escribe tu codigo dentro de esta funcion *
    }

    /* No mover nada */
    public static void testParImpar(int num, String resultadoEsperado) {
        String resultadoObtenido = verificarParImpar(num);
        System.out.println("Tu resultado es: " + resultadoObtenido);
        
        if (resultadoObtenido.equals(resultadoEsperado)) {
            System.out.println("Test passed.");
        } else {
            System.out.println("Test case not passed. Se esperaba: " + resultadoEsperado);
        }
    }
    
    public static void main(String[] args) {
        /* Escribe tu codigo en este espacio /*
         

        // No borrar
        String resultado = verificarParImpar(num);
        System.out.println(resultado);
        
        System.out.println("\n--- Ejecutando tests ---");
        testParImpar(4, "El numero 4 es par.");
        testParImpar(7, "El numero 7 es impar.");
        testParImpar(10, "El numero 10 es par.");
        testParImpar(15, "El numero 15 es impar.");
    }
}
```

2. Crea una funcion que permita sumar todos los elementos del array
   Copie el siguiente codigo.

```java
  import java.util.Scanner;

public class SumaArray {

    public static int sumarArray() {
       /* Escriba su codigo aqui */
    
    }

    public static void testSumarArray(int[] array, int resultadoEsperado) {
        int resultadoObtenido = 0;
        for (int i : array) {
            resultadoObtenido += i;
        }
        System.out.println("Tu resultado es: " + resultadoObtenido);
        
        // Comparamos el resultado obtenido con el esperado
        if (resultadoObtenido == resultadoEsperado) {
            System.out.println("Test passed.");
        } else {
            System.out.println("Test case not passed. Se esperaba: " + resultadoEsperado);
        }
    }

    public static void main(String[] args) {
        int resultado = sumarArray();
        
        System.out.println("\n--- Ejecutando tests ---");
        testSumarArray(new int[]{1, 2, 3, 4, 5}, 15);
        testSumarArray(new int[]{10, 20, 30}, 60);
        testSumarArray(new int[]{5, 5, 5, 5}, 20);
        testSumarArray(new int[]{0, 0, 0}, 0);
    }
}
```

