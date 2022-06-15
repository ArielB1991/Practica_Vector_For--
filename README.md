# Practica_Vector_For--
Practica OpenBootcamp

public class Main {
    public static void main(String[] args) {
        String palabra= "Queridos Amigos";
        System.out.println(regresar(palabra));
    }

    private static String regresar(String palabra) {
        String devolver ="";

        for (int i=palabra.length()-1; i>=0; i -- ){
            devolver += palabra.charAt(i) ;
        }
        return devolver;


    }



}



public class Vector {
    public static void main(String[] args) {

        String nombres[]=new String[6];

        nombres[0] = "Carlos";
        nombres[1] = "Raul";
        nombres[2] = "Alberto";
        nombres[3] = "Juan";
        nombres[4] = "Ricardo";
        nombres[5] = "Pedro";

        System.out.println( nombres[0]);
        System.out.println( nombres[1]);
        System.out.println( nombres[2]);
        System.out.println( nombres[3]);
        System.out.println( nombres[4]);
        System.out.println( nombres[5]);
        

    }
}
