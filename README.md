# Problem-3.T2021-2-3

 import java.util.Scanner;

public class SingleIntegerInput {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        System.out.print("Enter the value of a = ");
        int a = scanner.nextInt();

        System.out.print("Output: ");
        for (int i = 1; i <= a; i++) {
            int num = 2 * i - 1;
            if (i != a) {
                System.out.print(num + ", ");
            } else {
                System.out.print(num);
                
                scanner.close();
            }
        }
    }
}

