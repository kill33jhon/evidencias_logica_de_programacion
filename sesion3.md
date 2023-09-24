<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 3 


<!-- Su documentación aquí -->


# Actividad 3:


### Ejercicios de operaciones básicas en Java.


- Suma y multiplicación: Escribe un programa que solicite al usuario dos números enteros y luego imprima la suma y multiplicación de esos números.

- Resta y división: Escribe un programa que tome dos números enteros ingresados por el usuario y calcule la resta y división de esos números.

- Operaciones combinadas: Escribe un programa que solicite al usuario tres números enteros y realice las siguientes operaciones: suma de los tres números, multiplicación del primer número por el segundo y división del resultado entre el tercer número.

- Operaciones con decimales: Escribe un programa que solicite al usuario dos números decimales y realice las siguientes operaciones: suma, resta, multiplicación y división.

- Incremento y decremento: Escribe un programa que declare una variable entera y la inicialice con un valor. Luego, incrementa su valor en 1 y muestra el resultado. Después, decrementa su valor en 1 y muestra el resultado nuevamente.

- Operador de asignación compuesta: Escribe un programa que declare una variable entera y la inicialice con un valor. Utiliza el operador de asignación compuesta para sumar 5 a la variable y luego mostrar su valor.

- Operadores lógicos: Escribe un programa que tome dos valores booleanos ingresados por el usuario y muestre el resultado de las operaciones lógicas AND, OR y NOT entre esos valores.

- Operador ternario: Escribe un programa que tome un número entero ingresado por el usuario y utilice el operador ternario para determinar si el número es positivo o negativo. Luego, muestra el resultado en la salida.


# SOLUCION


### 1


```java
import java.util.Scanner;

    public class Operaciones {
        public static void main(String[] args) {
            Scanner input =  new Scanner(System.in);

        System.out.print("ingrese el numero entero: ");
        int numero1 = input.nextInt();

        System.out.print("ingrese un numero segundo entero: ");
        int numero2 = input.nextInt();
        
        int suma = numero1 + numero2;
        int multiplicacion = numero1 * numero2;

    
        System.out.println("la suma de los numeros " + suma);
        System.out.println("la multiplicacion es: " + multiplicacion);
    
    input.close();
            
        }
    }
```
### 2

```java

import java.util.Scanner;

public class RestaDivision {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        System.out.print("Ingrese el primer número entero: ");
        int numero1 = scanner.nextInt();

        System.out.print("Ingrese el segundo número entero: ");
        int numero2 = scanner.nextInt();

        int resta = numero1 - numero2;
        double division = (double) numero1 / numero2; // Usamos double para obtener decimales inexactos

        System.out.println("La resta de los números es: " + resta);
        System.out.println("La división de los números es: " + division);

        scanner.close();
    }
}
```

### 3

```java

import java.util.Scanner;

public class Operaciones {
    public static void main(String[] args) {
        Scanner input =  new Scanner(System.in);

        System.out.print("ingrese el primer valor booleano (true/false): ");
        boolean valor1 = input.nextBoolean();

        System.out.print("ingrese el segundo valor booleano (true/false): ");
        boolean valor2 = input.nextBoolean();

        // Operación lógica AND
        boolean resultadoOr = valor1 && valor2;
        System.out.println("Resultado de la operación ADN: " + resultadoAnd);

        // Operación logica OR
        boolean resultadoOr = valor1 || valor2;
        System.out.println("Resultado dela operacion OR: " + resutadoOr);

        // Operación lógica NOT para el primer valor 
        boolean resultadoNotValor1 = valor1;
        System.out.println("Resultado de la operación NOT para el primer valor: " + resultadoNotValor1);
        
        // Operacion lógica NOT para el segundo valor
        boolean resultadoNotValor2 = !valor2;
        System.out.println("Resultado de la operación NOT para el segundo valor: " + resultadoNotValor2);

        input.close();

        }
     }  
     
    ```
    ```
```
### 4


```java
import java.util.Scanner;

public class Operaciones {
    public static void main(String[] args) {
        Scanner input =  new Scanner(System.in);

        System.out.print("Ingresa el primer número decimal: ");
        double numero1 = input.nextDouble();

        System.out.print("Ingresa el segundo número decimal: ");
        double numero2 = input.nextDouble();

        double suma = numero1 + numero2;
        double resta = numero1 - numero2;
        double multiplicacion = numero1 * numero2;
        double division = numero1 / numero2;

        System.out.println("la suma de los numeros es: " + suma);
        System.out.println("la resta de los numeros es: " + resta);
        System.out.println("la multiplicacion de los numeros es: " + multiplicacion);
        System.out.println("la división de los numeros es: " + división);

        input.close();
        
       }

    }
```

### 5

```java

import java.util.Scanner;

public class Operaciones {
    public static void main(String[] args) {
        Scanner input =  new Scanner(System.in);

        System.out.print("ingrese el primer numero entero: ");
        int numero1 = input.nextInt();

        System.out.print("ingrese el segundo numero entero: ");
        int numero2 = input.nextInt();

        System.out.print("ingrese el tercer numero entero: ");
        int numero3 = input.nextInt();

        int suma = numero1 + numero2 + numero3;
        int multiplicacion = numero1 * numero2;
        double division = (double) multiplicacion / numero3;

        System.out.println("la suma de los tres numeros es: " + suma);
        System.out.println("la multiplicacion de primer numero por el segundo es: " + multiplicacion);
        System.out.println("la divicion del resultado entre el tercer numero es: " + division);

        input.close();
    }

}

```

### 6

```java
public class Operaciones {
    public static void main(String[] args) {
        int numero = 4;
     // Inicializamos la variable con un valor 

     System.out.println("valor inicial: " + numero);
     numero++; // Incremento en 1

     System.out.println("Despues del incremento: " + numero);
     numero--; // Decremento en 1
     System.out.println("Despues del decremento: " + numero);

      
    }
}
```
### 7

```java

import java.util.Scanner;

public class operadorTernario {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        System.out.print("Ingresa un numero entero: ");
        int numero = scanner.nextInt();

        String resultado = (numero >= 0) ? "positivo" : "negativo";
        System.out.println("El numero ingresado es: " + resultado);

        scanner.close();
    }
}

```

### 8

```java

import java.util.Scanner;

public class OperadoresLogicos {
    public static void main(String[] args) {
        Scanner input = new Scanner (System.in);

        System.out.print ("Ingrese el primer valor booleano: ");
        boolean valor1 = input.nextBoolean();

        System.out.print ("Ingrese el segundo valor booleano: ");
        boolean valor2 = input.nextBoolean();

        boolean operacionAnd = valor1 && valor2;
        System.out.println ("resultado de la operación AND: " + operacionAnd);

        boolean operacionOR = valor1 || valor2;
        System.out.println ("resultado de la operación OR: " + operacionOR);

        boolean operacionNOT1 = !valor1;
        System.out.println ("resultado de la operación NOT para el primer valor: " + operacionNOT1);

        boolean operacionNOT2 = !valor2;
        System.out.println ("resultado de la operación NOT para el primer valor: " + operacionNOT2);


        input.close ();
    }
}

```
