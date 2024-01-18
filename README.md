# modaba
import java.util.Scanner;

public class Modaba {

    public static void main(String[] args) {
        Scanner sc = new Scanner (System.in);
        System.out.println ("INTRUCE EL NUMERO DE VECES QUE QUIERES QUE SE REPITA");
        int modabas = sc.nextInt();
        for (int i =0; i < modabas;i++){
            System.out.print (" y modaba");
                for(int j = 0; j< i; j++){
                System.out.print ("a");
                }
                System.out.println ();
        }
    }
}
