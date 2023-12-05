# Marks.java
import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        calculateAverageMarks();
    }

    public static void calculateAverageMarks() {
        Scanner input = new Scanner(System.in);

        System.out.print("Enter marks for Java Programming: ");
        double javaMarks = input.nextDouble();
        System.out.print("Enter marks for Networking: ");
        double networkingMarks = input.nextDouble();
        System.out.print("Enter marks for Maths: ");
        double mathsMarks = input.nextDouble();

        double averageMarks = (javaMarks + networkingMarks + mathsMarks) / 3;

        System.out.println("Marks for Java Programming is: " + javaMarks);
        System.out.println("Marks for Networking is: " + networkingMarks);
        System.out.println("Marks for Maths is: " + mathsMarks);
        System.out.println("The average is: " + averageMarks);
    }
}
