Leap year checker



import java.util.Scanner;

public class LeapYearChecker {
    public static void main(String args) {
        // Creating a Scanner object to read user input
        Scanner scanner = new Scanner(System.in);
        
        System.out.print("Enter a year: ");
        int year = scanner.nextInt();
        
        if (isLeapYear(year)) {
            System.out.println("The year you entered is a leap year");
        } else {
            System.out.println("The year you entered is not a leap year");
        }
        
        // Closing the Scanner object
        scanner.close();
    }
    
    public static boolean isLeapYear(int year) {
        // Leap year condition
        if ((year % 4 == 0 && year % 100 != 0) || (year % 400 == 0)) {
            return true;
        } else {
}
}
}Leap year checker



import java.util.Scanner;

public class LeapYearChecker {
    public static void main(String args) {
        // Creating a Scanner object to read user input
        Scanner scanner = new Scanner(System.in);
        
        System.out.print("Enter a year: ");
        int year = scanner.nextInt();
        
        if (isLeapYear(year)) {
            System.out.println("The year you entered is a leap year");
        } else {
            System.out.println("The year you entered is not a leap year");
        }
        
        // Closing the Scanner object
        scanner.close();
    }
    
    public static boolean isLeapYear(int year) {
        // Leap year condition
        if ((year % 4 == 0 && year % 100 != 0) || (year % 400 == 0)) {
            return true;
        } else {
}
}
}
