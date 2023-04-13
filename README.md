# HarmonicNumber
    import java.util.Scanner;
    public class Main {
    public static void main(String[] args) {
     
      Scanner input = new Scanner(System.in);
        System.out.print("n sayısını giriniz: ");
        double number= input.nextDouble();
        double result =0;
        for (double i =1; i<=number; i++){
            result += (1/i);
        }
        System.out.print(result);
    }
    }
