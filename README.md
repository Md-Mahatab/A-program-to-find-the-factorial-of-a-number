package com.mycompany.task_5;

import java.util.Scanner;

public class factorial_number {
    public static void main(String[] args) {

        Scanner input = new Scanner(System.in);
        System.out.print("Enter any number = ");

        int num = input.nextInt();
        long factorial = 1;

        for (int i = 1; i <= num; i++) {
            factorial *= i;
        }

        System.out.println("Factorial of " + num + " is: " + factorial);
    }
}
