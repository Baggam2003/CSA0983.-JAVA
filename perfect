import java.util.*;

public class Perfect {
    public static void main(String[] args) {
        Scanner s = new Scanner(System.in);
        System.out.println("Enter the number:");
        int n = s.nextInt();
        int sum = 0;

        for (int i = 1; i <= n / 2; i++) {
            if (n % i == 0) {
                sum += i;
            }
        }

        if (sum == n) {
            System.out.println("The given number is a perfect number");
        } else {
            System.out.println("The given number is not a perfect number");
        }
    }
}
