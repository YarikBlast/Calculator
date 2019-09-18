# Calculator
package com.company;
import java.util.Scanner;


 public class Name {

     public static void main(String[] args) {

         Scanner num = new Scanner(System.in);
         double result = 0;
         double a;
         double b;
         int d = 0;
         int t = 1;
         while (t == 1)
         {
         System.out.println("Чтобы продожить напишите 1.Хотите завершить напишите 2");
         d = num.nextInt();

         if (1 == d) {
             System.out.println("введите число 1");
             a = num.nextDouble();
             System.out.println("введите число 2");
             b = num.nextDouble();
             System.out.println("введите действие (+, -, * или /)");
             String operation = num.next();
             switch (operation) {
                 case "+":
                     result = (a + b);
                     break;
                 case "-":
                     result = (a - b);
                     break;
                 case "*":
                     (result) = (a * b);
                     break;
                 case "/":
                     if (b == 0) {
                         System.out.println("Error");
                     } else {
                         (result) = (a / b);
                     }
                     System.out.println("ответ: " + result);
             }

         } else if (d == 2) {
             return;
         }
     }
     }
 }
