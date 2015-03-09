# numeros-primos

package numerosprimos;
import java.util.*;

public class NumerosPrimos {

    
    public static void main(String[] args) {
        Scanner lec=new Scanner(System.in);
        int N,C=1,P=0;
        
        System.out.print("Ingrese un Número: ");
        N=lec.nextInt();
        
        while(C<=N){
        if(N%C==0){
         P++;   
          C++;  
        }
        C++;
        } 
        if(P==2){
        
          System.out.println("El número es Primo");
        } System.out.println("El número no es Primo");   
    }
    
}
