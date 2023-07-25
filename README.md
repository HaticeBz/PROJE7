import java.util.Scanner;
public class Main {
        public static void main(String[] args){
                Scanner input = new Scanner(System.in) ;
                int kenar1, kenar2 ;
                double hipotenus ;
                System.out.print("1.kenarın uzunluğu :") ;
                kenar1 = input.nextInt() ;
                System.out.print("2.kenarın uzunluğu :") ;
                kenar2 = input.nextInt();
                hipotenus = Math.sqrt((kenar1 * kenar1) + (kenar2 * kenar2))  ;
                System.out.print("Hipotenüs : " + hipotenus) ;
        }
}
