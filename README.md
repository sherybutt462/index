# index
creating repository
package numberss;

public class Number2 {

    public static void main(String[] args) {
        System.out.println(strongNumber(145));
    }

    public static int factorial(int a) {

        int i, fact = 1;

        for (i = 1; i <= a; i++) {
            fact = fact * i;
        }

        return fact;
    }

    public static int strongNumber(int num) {

        int i;
        int sum = 0;
        boolean strong;
        int temp = num;

        for (i = 1; i <= String.valueOf(num).length(); i++) {

            System.out.println("LOOP " + i);

            temp = temp % 10;

            System.out.println("temp = %%% " + temp);

            sum += factorial(temp);
            temp = num / 10;

            System.out.println("temp /// = " + temp);

        } 
        HELLO AYESHA TREAT KAB DO GY?
}
