
public class PrinterApp {
    public static void main(String[] args) {
        // Step 4: Declare a string typed variable and assign your name to it.
        String creator = "Your Name";

        // Step 2: Print "Printer App" to the console.
        System.out.println("Printer App");

        // Step 3: Print "This app is made by:" to the console.
        System.out.println("This app is made by:");

        // Step 5: Print the value of the creator on the same line as "This app is made by:".
        System.out.print("This app is made by: " + creator);

        // Step 6: Declare two numeric variables, number1 and number2, and assign values.
        int number1 = 5;
        int number2 = 2;

        // Step 7: Print the value of number1 to the console (commented out).
        // System.out.println("The value of number1 is " + number1);

        // Step 8: Print the value of number1 with a message.
        System.out.println("The value of number1 is " + number1);

        // Step 9: Print the value of number2 with a message.
        System.out.println("The value of number2 is " + number2);

        // Step 10: Declare an integer typed variable called multiplication.
        int multiplication;

        // Step 11: Multiply number1 and number2 and assign the result to the multiplication variable.
        multiplication = number1 * number2;

        // Step 12: Print the multiplication result.
        System.out.println(number1 + " * " + number2 + " = " + multiplication);

        // Step 13: Repeat for addition, division, and subtraction.
        int addition = number1 + number2;
        double division = (double) number1 / number2; // Use double for accurate division.
        int subtraction = number1 - number2;

        System.out.println(number1 + " + " + number2 + " = " + addition);
        System.out.println(number1 + " / " + number2 + " = " + division);
        System.out.println(number1 + " - " + number2 + " = " + subtraction);
    }
}
