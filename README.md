import static java.time.Clock.system;
import java.util.Scanner;


public class Menu {

    public static void main(String[] args) {
        Scanner leer = new Scanner(System.in);
        int respuesta;
        respuesta = leer.nextInt();
        System.out.print("Presione 1 para suma");
        System.out.print("Presione 2 para resta");
        System.out.print("Presione 3 para multiplicación");
        System.out.print("Presione 4 para división");
        switch (respuesta) {
            case 1:
                System.out.print("Ha seleccionado suma");
                int suma;
                int a;
                a = leer.nextInt();
                int b;
                b = leer.nextInt();
                suma = a + b;
                System.out.print("La suma es: " + suma);
                break;

            case 2:
                System.out.print("Ha seleccionado resta");
                int resta;
                int c;
                c = leer.nextInt();
                int d;
                d = leer.nextInt();
                suma = c - d;
                System.out.print("La resta es: " + resta);
                break;

            case 3:
                System.out.print("Ha seleccionado multiplicacion");
                int multiplicacion;
                int e;
                e = leer.nextInt();
                int f;
                f = leer.nextInt();
                suma = e * f;
                System.out.print("La multiplicacion es: " + multiplicacion);
                break;

            case 4:
                System.out.print("Ha seleccionado division");
                int division;
                int g;
                g = leer.nextInt();
                int h;
                h = leer.nextInt();
                suma = g / h;
                System.out.print("La division es: " +division);
                break;

        }
    }
}
1
