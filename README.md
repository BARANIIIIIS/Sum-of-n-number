# Sum-of-n-numberfghhhfg
import java.util.Scanner;

public class SumOfTwoNumbers {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        // Input first number
        System.out.print("Enter the first number: ");
        int num1 = scanner.nextInt();

        // Input second number
        System.out.print("Enter the second number: ");
        int num2 = scanner.nextInt();

        // Calculate sum
        int sum = num1 + num2;

        // Display result
        System.out.println("The sum of " + num1 + " and " + num2 + " is: " + sum);
    }
}
