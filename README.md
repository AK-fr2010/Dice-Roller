# Dice-Roller
Rolls a dice giving you a random number 

     import java.util.Random;
       public class Main {
        public static void main(String[]args){
         Random random = new Random();

        int number = random.nextInt(1,7);

        if(number == 1){
            System.out.print("The Number is 1");
        }
        else if(number == 2) {
            System.out.println("The Number is 2");
        }
        else if(number == 3) {
            System.out.println("The Number is 3");
        }
        else if(number == 4) {
            System.out.println("The Number is 4");
        }
        else if(number == 5) {
            System.out.println("The Number is 5");
        }
        else{
            System.out.print("The Number is 6");
        }
    }
}
