# SwitchCase code in java
import java.util.*;

public class Main {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        System.out.print("Enter a number1 : ");
        int button = sc.nextInt();
        switch (button){
            case 1 :
            System.out.println("Hello");
            break;
            case 2 :
            System.out.println("Namaste");
            break;
            case 3 :
            System.out.print("Bonjour");
            break;
            default :
            System.out.print("Inavalid case");
        }
    }
}
