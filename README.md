# en-b-y-k-say-en-k-k-say-
import java.util.Scanner;

public class Main {
    public static void main(String[] args) {

        Scanner input = new Scanner(System.in);
        int counter,number, min =1, max=1;

        System.out.print("Kaç sayı gireceksiniz :");
        counter = input.nextInt();

        for (int i=1; i<=counter; i++){
            System.out.print( i + "sayı giriniz :");
            number = input.nextInt();

            if (i == 1){

                min = number;
                max = number;

            }
            if ( number < min){
                min = number;

            }
            if (number > max){
                max = number;
            }

        }
        System.out.print( "En küçük sayı :" + min);
        System.out.print( "En büyük sayı :" + max);



    }
}
