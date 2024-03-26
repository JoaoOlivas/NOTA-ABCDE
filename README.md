import java.util.Scanner;

public class nota {
    
    public static void main(String[] args) {
        
        Scanner scanner = new Scanner(System.in);

        double nota;
        
            System.out.print("Digite a nota (entre 0 e 10): ");
            
            nota = scanner.nextDouble();
            
         if(nota < 0 || nota > 10) System.out.println("esse numero é invalido deve ser um valor de 0 á 10 " ); 

        String conceito;

        if (nota >= 9.0 && nota <= 10.0) System.out.println("Sua nota é A ");
            
        
         else if (nota >= 7.0 && nota < 9.0) System.out.println("Sua nota é B ");
            
          
         else if (nota >= 5.0 && nota < 7.0) System.out.println("Sua nota é C ");
            

         else if (nota >= 3.0 && nota < 5.0) System.out.println("Sua nota é D ");
        
            
         else if (nota >= 0 && nota < 3.0) System.out.println("Sua nota é E ");
            
      
    }
    
}
