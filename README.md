# L-gica-de-Programa-o
códigos da aula de LP (Busca Sequêncial)


package java55;

import java.util.Scanner;
import java.util.Random;

public class Java55 {
    public static void main(String[] args) {
        Random aleatorio = new Random();
        Scanner tcl = new Scanner(System.in);
        int vetor [] = new int [10];
        
        System.out.println("Digite o valor que você deseja encontrar");
        int valor = tcl.nextInt();
        
        boolean encontrado = false;
        
        for (int i = 0; i < vetor.length; i++){
            if (valor == vetor [i]) {
                System.out.println("Valor encontrado");
                encontrado = true;
                break;
            }
        }
               
       if (encontrado == false){
           System.out.println("Valor não encontrado");
       }
    }
    
}
