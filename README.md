# cin-takvimi
import java.util.Scanner;
public class Main {
    public static void main (String[]args) {
        int year,result;
        Scanner input= new Scanner(System.in);
        System.out.println("Doğum tarihini giriniz: ");
        year= input.nextInt();
        result= year %12;
        switch (result){
            case 1 :
                System.out.println("maymun ");
                break;
            case 2 :
                System.out.println("horoz ");
                break;
            case 3 :
                System.out.println("köpek ");
                break;
            case 4 :
                System.out.println("domuz ");
                break;
            case 5 :
                System.out.println("fare ");
                break;
            case 6 :
                System.out.println("öküz ");
                break;
            case 7:
                System.out.println("kaplan ");
                break;
            case 8:
                System.out.println("tavşan ");
                break;
            case 9 :
                System.out.println("ejderha ");
                break;
            case 10 :
                System.out.println("maymun ");
                break;
            case 11 :
                System.out.println("at");
                break;
            case 12 :
                System.out.println("koyun ");
                break;
        }
        }
    }
