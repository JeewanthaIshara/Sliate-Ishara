# Sliate-Ishara
This is my Sliate Ripository

// 01

class Main {
    public static void main(String[] args) {
    
    String name = "Jeewantha Ishara";
        int age = 22;
        String school = "Mayurapada Central";
        String hobby = "Coding";

        System.out.println("Name: " + name);
        System.out.println("Age: " + age);
        System.out.println("School: " + school);
        System.out.println("Hobby: " + hobby);
   
    
    }
}


// 02

import java.util.Scanner;

public class Q2 {
    public static void main(String[] args) {
        Scanner input = new Scanner(System.in);
        System.out.print("Enter your name: ");
        String name = input.nextLine();
        System.out.println("My name is " + name);
    }
}

// 03

public class Q3 {
    public static void main(String[] args) {
        System.out.println(-5 + 8 * 6);
        System.out.println((55+9) % 9); 
        System.out.println(20 + -3*5 / 8); 
        System.out.println(5 + 15 / 3 * 2 - 8 % 3); 
    }
}


// 04

import java.util.Scanner;

public class Q4 {
    public static void main(String[] args) {
        Scanner input = new Scanner(System.in);

        System.out.print("Enter first number: ");
        int a = input.nextInt();

        System.out.print("Enter second number: ");
        int b = input.nextInt();

        System.out.println("Sum: " + (a + b));
        System.out.println("Difference: " + (a - b));
        System.out.println("Multiplication: " + (a * b));
        System.out.println("Division: " + (a / b));
        System.out.println("Remainder: " + (a % b));
    }
}



// 05
import java.util.Scanner;
import java.time.Year;

public class Q5 {
    public static void main(String[] args) {
        Scanner input = new Scanner(System.in);

        System.out.print("Enter your name: ");
        String name = input.nextLine();

        System.out.print("Enter your age: ");
        int age = input.nextInt();

        int currentYear = Year.now().getValue();
        int yearTurn100 = currentYear + (100 - age);

        System.out.println("Hello " + name + ", you will turn 100 years old in " + yearTurn100);
    }
}

// 06

public class Q6 {
    public static void main(String[] args) {
        double radius = 7.5;
        double area = 3.14 * radius * radius;
        double perimeter = 2 * 3.14 * radius;

        System.out.println("Area of the circle: " + area);
        System.out.println("Perimeter of the circle: " + perimeter);
    }
}

// 07

import java.util.Scanner;

public class Q7 {
    public static void main(String[] args) {
        Scanner input = new Scanner(System.in);

        System.out.print("Enter Science marks: ");
        int science = input.nextInt();
        System.out.print("Enter Maths marks: ");
        int maths = input.nextInt();
        System.out.print("Enter English marks: ");
        int english = input.nextInt();
        System.out.print("Enter IT marks: ");
        int it = input.nextInt();
        System.out.print("Enter History marks: ");
        int history = input.nextInt();

        int total = science + maths + english + it + history;
        double average = total / 5.0;

        System.out.println("Total Marks: " + total);
        System.out.println("Average Marks: " + average);

        String grade;
        if (average < 45) {
            grade = "F";
        } else if (average < 55) {
            grade = "S";
        } else if (average < 65) {
            grade = "C";
        } else if (average < 75) {
            grade = "B";
        } else {
            grade = "A";
        }

        System.out.println("Grade: " + grade);
    }
}


