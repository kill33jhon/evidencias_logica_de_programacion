<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 4


<!-- Su documentación aquí -->


# Actividad 4: 


### Ejercicios de control de flujo con expresiones compuestas

- Determinar si el estudiante es mayor de edad y tiene un estado activo.
- Determinar si el estudiante tiene una beca o una carrera relacionada con el desarrollo de software.
- Determinar si el estudiante está en el último semestre de su carrera y tiene un estado activo.
- Determinar si el estudiante tiene una carrera relacionada con el desarrollo de software y un promedio superior a 4.0.
- Mostrar toda la información del estudiante si está matriculado en el Cesde.
- Asignar una beca del 50% si el estudiante está matriculado en el Cesde, tiene un promedio superior a 4.0 y está activo.

### Determinar la cantidad de beca que recibe el estudiante según su promedio:
- 0.0 - 3.4: El estudiante no recibe beca.
- 3.5 - 3.9: El estudiante recibe una beca parcial del 25%.
- 4.0 - 4.4: El estudiante recibe una beca parcial del 50%.
- 4.5 - 5.0: El estudiante recibe una beca completa.



# SOLUCIONES


### SOLUCION 1

```java

public class Actividad4JhonnyPerez {

    public static public static void main(String[] args) {
        
    


// Variables de tipo String
String nombre = "Jhonny Perez";
String apellido = "Santana";
String identificación = "1088278248";
String correo = "jhonkill205@gmail.com";
String carrera = "Desarrollo de Software";
String universidad = "Cesde";
// Variable de tipo int
int edad = 33;
// Variable de tipo boolean
boolean esActivo = true;
boolean becado = false;
// Variable de tipo char
char género = 'M';
// Variable de tipo double
double promedio = 4.5;
// Variable de tipo int
int semestre = 2;

System.out.println("---");
System.println.("Ejercicio 1");

if (edad >= 33 && esActivo) {
    Sysyem.out.println("Es mayor de edad y es activo");

}

System.out.println("---") {
System.out.println("Ejercicio 2");

if (!becado || "Desarrollador" .equals(carrera));
System.out.prinln("El estudiante tiene beca o estudia derarrollo de software");

}

System.out.println("---");
System.out.println("Ejercicio 3");

if (semestreActual == semestresTotales && estado.equals("activo")) {
    System.out.println("El estudiante esta en el ultimo semestre y tiene un estado activo");


}

System.out.println("---");
System.out.println("Ejercicio 4");

 if (carrera.toLowerCase().contains("desarrollo de software") && promedio > 4.0) {
    System.out.println("El estudiante tiene una carrera relacionada con el desarrollo de software y tiene un promedio superior a 4.0.");
 }

 System.out.println("---")
 System.println("Ejercicio 5");

 if ("Cesde".equals(universidad)){

System.out.println("Información del estudiante:");
System.out.println("Nombre");
System.out.println("Apellido");
System.out.println("identificación");
System.out.println("Correo");
System.out.println("Carrera");

 }
System.out.println("---")
System.out.println("Ejercicio 6")

if ("Cesde".equals(universidad) && promedio > 4.0  && esActivo) {
    System.out.println("El estudiante tiene una beca del 50%");
}

System.out.println("---");
System.out.println("Ejercicio 7");

if(promedio >= 4.5){
    System.out.println("Tiene una beca para estudiar desarrollo");
}


    }
}
```

# SOLUCION 2

```java

import java.util.Scanner;

public class MesesAño {

    public static void main(String[] args) {
        Scanner Scanner = new Scanner(System.in);

        System.out.println("Ingrese un mes del año:");
        String mes = Scanner.nextLine();

        switch (mes) {
            case "enero":
                System.out.println("1");
                break;
            case "febrero":
               System.out.println("2");
                break;
            case "marzo":
                System.out.println("3");
                break;
            case "abril":
                System.out.println("4");
                break;
            case "mayo":
                System.out.println("5");
                break;
            case "junio":
                System.out.println("6");
                break;
            case "julio":
                System.out.println("7");
                break;
            case "agosto":
                System.out.println("8");
                break;
            case "septiembre":
                System.out.println("9");
                break;
            case "octubre":
                System.out.println("10");
                break;
            case "noviembre":
                System.out.println("11");
                break;
            case "diciembre":
                System.out.println("12");
                break; 
            default:
                System.out.println("mes no valido");

        }

    }
}
```

### SOLUCION 3

```java

import java.util.Scanner;

public class NumeroMes {
    public static void main(String[] args) {
        Scanner Scanner = new Scanner(System.in);

        System.out.println("Ingrese un numero:");
        String mes = Scanner.nextLine();

        switch (mes) {
            case "1":
                System.out.println("enero");
                break;
            case "2":
            System.out.println("febrero");
            case "3":
            System.out.println("marzo");
            break;
        case "4":
            System.out.println("abril");
            break;
        case "5":
            System.out.println("mayo");
            break;
        case "6":
            System.out.println("junio");
            break;
        case "7":
            System.out.println("julio");
            break;
        case "8":
            System.out.println("agosto");
            break;
        case "9":
            System.out.println("septiembre");
            break;
        case "10":
            System.out.println("octubre");
            break;
        case "11":
            System.out.println("noviembre");
            break;
        case "12":
            System.out.println("diciembre");
            break; 
              
            default:
                System.out.println("mes no valido");

        }

    }
}
```
