
import java.util.Scanner;

public class Multiplos3 {
    public static void main(String[] args){

        Scanner sc = new 
Scanner(System.in);
              
             int a, b;

             System.out.print("digite o primeiro numero: ");
             a = sc.nextInt();

             System.out.print("digite o segundo numero: ");
             b = sc.nextInt();

             for(int i = a; i <= b; i++){
                if(i % 3 == 0){
                    System.out.println(i);
                }

             }
    }

    
}
