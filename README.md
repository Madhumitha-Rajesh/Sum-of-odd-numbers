# Sum-of-odd-numbers
public class SumOfOddNumbers {
    public static void main(String[] args) {
        int sum = 0;
        for (int i = 1; i <= 100;i++) {
        if (i % 2 != 0) {
                sum += i; // Add odd numbers to the sum
            }
        }
        System.out.println("The sum of odd numbers between 1 and 100 is: " + sum);
    }
}

output- 

The sum of odd numbers between 1 and 100 is: 2500
