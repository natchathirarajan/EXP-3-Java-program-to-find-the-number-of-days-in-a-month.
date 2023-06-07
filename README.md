# EXP-3-Java-program-to-find-the-number-of-days-in-a-month.

## AIM:
To write a java program to find the number of days in a month.
## ALGORITHM: 
### Step 1:
Import the necessary packages.
### Step 2: 
Get the value from the user.
### Step 3: 
Find the number of days in a month using switch case.
### Step 4:  
Print the result.
### Step 5: 
End the program.
## PROGRAM:
~~~
Name   : H.Syed Abdul Wasih
Reg No : 212221240057
~~~
~~~
import java.util.Scanner;
public class Main {
    public static void main(String[] args)
    {
        Scanner s= new Scanner(System.in);
        System.out.print("Enter the month number: ");
        int month = s.nextInt();
        switch (month) {
            case 1:
                System.out.println("January has 31 days.");
                break;
            case 2:
                System.out.println("February has 28 days or 29 days.");
                break;
            case 3:
                System.out.println("March has 31 days.");
                break;
            case 4:
                System.out.println("April has 30 days");
                break;
            case 5:
                System.out.println("May has 31 days");
                break;
            case 6:
                System.out.println("June has 30 days");
                break;
            case 7:
                System.out.println("July has 31 days");
                break;
            case 8:
                System.out.println("August has 31 days");
                break;
            case 9:
                System.out.println("September has 30 days");
                break;
            case 10:
                System.out.println("October has 31 days");
                break;
            case 11:
                System.out.println("November has 30 days");
                break;
            case 12:
                System.out.println("December has 31 days");
                break;
            default:
                System.out.println("Invalid number");
        }

    }
}
~~~

## OUTPUT:

![3](https://github.com/abdulwasih2003/EXP--3-Java-program-to-find-the-number-of-day-in-a-month/assets/91781810/75be0368-ae73-4094-8a9c-194c0e5bd633)

## RESULT:
Thus the java program to print the even numbers between 1-20 is successful.
