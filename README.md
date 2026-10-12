public class j14_CicloForEach_esunForsimple {
    public static void main(String[] args) {

        // Declaramos un arreglo de nombres
        String[] nombres = {"Ana", "Luis", "Carlos", "María", "Sofía"};

        System.out.println("Con For Each");
        System.out.println("----------------------------");
        // El ciclo for-each recorre automáticamente
        // cada elemento del arreglo.
        for (String nombre : nombres) { // para cada nombre en la lista nombres
            // En cada iteración, la variable "nombre"
            // almacena uno de los elementos del arreglo.
            System.out.println("Hola " + nombre);
        }


        System.out.println("----------------------------");
        System.out.println("Con For tradicional");

        // Recorremos el arreglo utilizando índices
        for (int i = 0; i < nombres.length; i++) {
            System.out.println("Hola " + nombres[i]); // imprime el nombre en la posición i
        }

        System.out.println("----------------------------");
        System.out.println("Con For Each (Apellidos)");
        System.out.println("----------------------------");
        
        String[] apellidos = {"Gómez", "Pérez", "López", "Hernández", "Martínez"};
        
        for (String apellido : apellidos) {
            System.out.println("Apellido: " + apellido);
        }

        System.out.println("----------------------------");
        System.out.println("Con For tradicional (Apellidos)");
        
        for (int i = 0; i < apellidos.length; i++) {
            System.out.println("Apellido: " + apellidos[i]);
        }

        System.out.println("----------------------------");
        System.out.println("Con Do-While");
        System.out.println("----------------------------");

        int contador = 10;

        do {
            System.out.println("Número: " + contador);
            contador++;
        } while (contador <= 5);


        System.out.println("----------------------------");
        // Este mensaje se imprime cuando el ciclo termina
        System.out.println("Fin del programa.");
        System.out.println("----------------------------");

    }
}
