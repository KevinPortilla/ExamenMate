package Numero;

import java.util.Scanner;

public class Multiplo {

    public static void main(String[] args) {
        Scanner Multiplo = new Scanner(System.in);
        int N;
        System.out.print("Número: ");
        N = Multiplo.nextInt();
        if(N%5==0)
           System.out.println("Es múltiplo de 5");   
        else
           System.out.println("No es múltiplo de 5");
    }
    
}
