




import java.util.Scanner;
         public class whileLoop {
         
         public static void main(String[] args) {

            Scanner scan = new Scanner(System.in);

            System.out.print("Input your age: ");

            while (!scan.hasNextInt()) {
                // ignore the invalid inputs because of ! (excl. mark)
                scan.next();
                System.out.print("Only integers allowed. Try again: ");
            }
            // save the input
            int age = scan.nextInt();

            System.out.println("You are " + age);

        }
    }

