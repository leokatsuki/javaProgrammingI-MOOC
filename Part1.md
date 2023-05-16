# Java Programming I - University of Helsinki MOOC

## Exercises Part 1

#### Sandbox
```java
public class Sandbox {

    public static void main(String[] args) {
        // Write your program here
    }
}
```

#### AdaLovelace
```java
public class AdaLovelace {
 
    public static void main(String[] args) {
        // Write your program here
        System.out.println("Ada Lovelace");
    }
}
```

#### OnceUponATime
```java
public class OnceUponATime {
 
    public static void main(String[] args) {
        // Write your program here
        System.out.println("Once upon a time");
        System.out.println("there was");
        System.out.println("a program");
        
    }
}
```

#### Dinosaur
```java
public class Dinosaur {
 
    public static void main(String[] args) {
        // Write your program here
        System.out.println("Once upon a time");
        System.out.println("there was");
        System.out.println("a dinosaur");
    }
}
```

#### Message
```java
public class Message {
 
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
 
        System.out.println("Write a message:");
        // Write your program here
        
        String message = scanner.nextLine();
        
        System.out.println(message);
 
    }
}
```

#### HiAdaLovelace
```java
public class HiAdaLovelace {
 
    public static void main(String[] args) {
        String name = "Ada Lovelace!";
 
        System.out.println("Hi " + name);
    }
}
```

#### MessageThreeTimes
```java
public class MessageThreeTimes {
 
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
 
        System.out.println("Write a message:");
        // Write your program here
        String message = scanner.nextLine();
        
        System.out.println(message);
        System.out.println(message);
        System.out.println(message);
    }
}
```

#### Greeting
```java
public class Greeting {
 
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
 
        // Write your program here
        System.out.println("What's your name?");
        
        String message = scanner.nextLine();
        
        System.out.println("Hi " + message);
    }
}
```

#### Conversation
```java
public class Conversation {
 
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
 
        // Write your program here
        System.out.println("Greetings! How are you doing?");
        String first = scanner.nextLine();
        System.out.println("Oh, how interesting. Tell me more!");
        String second = scanner.nextLine();
        System.out.println("Thanks for sharing!");
    }
}
```

#### Story
```java
public class Story {
 
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
 
        // Write your program here
        System.out.println("I will tell you a story, but I need some information    first.");
        System.out.println("What is the main character called?");
        String first = scanner.nextLine();
        System.out.println("What is their job?");
        String second = scanner.nextLine();
        System.out.println("Here is the story: ");
        System.out.println("Once upon a time there was " + first + ", who was " + second + ".");
        System.out.println("On the way to work, " + first + " reflected on life.");
        System.out.println("Perhaps " + first + " will not be " + second + " forever.");
    }
}
```

#### VariousVariables
```java
public class VariousVariables {
 
    public static void main(String[] args) {
        // MODIFY THESE:
 
        int numberOfChicken = 9000;
        double baconWeight = 0.1;
        String tractor = "Zetor";
 
        // DON'T MODIFY THESE:
        System.out.println("Chicken:");
        System.out.println(numberOfChicken);
        System.out.println("Bacon (kg):");
        System.out.println(baconWeight);
        System.out.println("Tractor:");
        System.out.println(tractor);
        System.out.println("");
        System.out.println("And finally, a summary:");
        System.out.println(numberOfChicken);
        System.out.println(baconWeight);
        System.out.println(tractor);
    }
}
```

#### IntegerInput
```java
public class IntegerInput {
 
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
 
        // write your program here
        System.out.println("Give a number:");
        int number = Integer.valueOf(scanner.nextLine());
        System.out.println("You gave the number " + number);
    }
}
```

#### DoubleInput
```java
public class DoubleInput {
 
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
 
        // write your program here
        System.out.println("Give a number:");
        double number = Double.valueOf(scanner.nextLine());
        System.out.println("You gave the number " + number);
    }
}
```

#### BooleanInput
```java
public class BooleanInput {
 
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
 
        // write your program here
        System.out.println("Write something:");
        boolean value = Boolean.valueOf(scanner.nextLine());
        System.out.println("True or false? " + value);
    }
}
```

#### DifferentTypesOfInput
```java
public class DifferentTypesOfInput {
 
    public static void main(String[] args) {
        Scanner scan = new Scanner(System.in);
 
        // Write your program here
        System.out.println("Give a string:");
        String text = scan.nextLine();
        System.out.println("Give an integer:");
        int number = Integer.valueOf(scan.nextLine());
        System.out.println("Give a double:");
        double number2 = Double.valueOf(scan.nextLine());
        System.out.println("Give a boolean:");
        boolean value = Boolean.valueOf(scan.nextLine());
        System.out.println("You gave the string " + text);
        System.out.println("You gave the integer " + number);
        System.out.println("You gave the double " + number2);
        System.out.println("You gave the boolean " + value);
    }
}
```

#### SecondsInADay
```java
public class SecondsInADay {
 
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
 
        // Write your program here
        System.out.println("How many days would you like to convert to seconds?");
        int days = Integer.valueOf(scanner.nextLine());
        int seconds = days*24*60*60;
        System.out.println(seconds);
    }
}
```

#### SumOfTwoNumbers
```java
public class SumOfTwoNumbers {
 
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
 
        // Write your program here
        System.out.println("Give the first number:");
        int number = Integer.valueOf(scanner.nextLine());
        System.out.println("Give the second number:");
        int number2 = Integer.valueOf(scanner.nextLine());
        System.out.println("The sum of the numbers is " + (number + number2));
    }
}
```

#### SumOfThreeNumbers
```java
public class SumOfThreeNumbers {
 
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
 
        // Write your program here
        System.out.println("Give the first number:");
        int number = Integer.valueOf(scanner.nextLine());
        System.out.println("Give the second number:");
        int number2 = Integer.valueOf(scanner.nextLine());
        System.out.println("Give the third number:");
        int number3 = Integer.valueOf(scanner.nextLine());
        System.out.println("The sum of the numbers is " + (number + number2 + number3));
    }  
}
```

#### AdditionFormula
```java
public class AdditionFormula {
 
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
 
        // write your program here
        System.out.println("Give the first number:");
        int number = Integer.valueOf(scanner.nextLine());
        System.out.println("Give the second number:");
        int number2 = Integer.valueOf(scanner.nextLine());
        System.out.println(number + " + " + number2 + " = " + (number+number2));
    }
}
```

#### MultiplicationFormula
```java
public class MultiplicationFormula {
 
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
 
        // Write your program here
        System.out.println("Give the first number:");
        int number = Integer.valueOf(scanner.nextLine());
        System.out.println("Give the second number:");
        int number2 = Integer.valueOf(scanner.nextLine());
        System.out.println(number + " * " + number2 + " = " + (number*number2));
    }
}
```

#### AverageOfTwoNumbers
```java
public class AverageOfTwoNumbers {
 
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
 
        // Write your program here
        System.out.println("Give the first number:");
        int number = Integer.valueOf(scanner.nextLine());
        System.out.println("Give the second number:");
        int number2 = Integer.valueOf(scanner.nextLine());
        System.out.println("The average is " + (((double) number + number2)/2));
    }
}
```

#### AverageOfThreeNumbers
```java
public class AverageOfThreeNumbers {
 
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
 
        // Write your program here
        System.out.println("Give the first number:");
        int number = Integer.valueOf(scanner.nextLine());
        System.out.println("Give the second number:");
        int number2 = Integer.valueOf(scanner.nextLine());
        System.out.println("Give the third number:");
        int number3 = Integer.valueOf(scanner.nextLine());
        System.out.println("The average is " + (((double) number + number2 + number3) / 3));
    }
}
```

#### SimpleCalculator
```java
public class SimpleCalculator {
 
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
 
        // Write your program here
        System.out.println("Give the first number:");
        int number = Integer.valueOf(scanner.nextLine());
        System.out.println("Give the second number:");
        int number2 = Integer.valueOf(scanner.nextLine());
        System.out.println(number + " + " + number2 + " = " + (number + number2));
        System.out.println(number + " - " + number2 + " = " + (number - number2));
        System.out.println(number + " * " + number2 + " = " + (number * number2));
        System.out.println(number + " / " + number2 + " = " + (1.0 * number / number2));
    }
}
```

#### SpeedingTicket
```java
public class SpeedingTicket {
 
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
 
        // Write your program here.
        System.out.println("Give speed:");
        int speed = Integer.valueOf(scanner.nextLine());
        if(speed > 120){
            System.out.println("Speeding ticket!");
        }
    }
}
```

#### CheckYourIdentation
```java
public class CheckYourIndentation {
 
    public static void main(String[] args) {
        Scanner scan = new Scanner(System.in);
 
        System.out.println("Give a number: ");
        int first = Integer.valueOf(scan.nextLine());
        System.out.println("Give another number: ");
        int second = Integer.valueOf(scan.nextLine());
        if (first == second) {
            System.out.println("Same!");
        } else if (first > second) {
            System.out.println("The first was larger than the second!");
        } else {
            System.out.println("The second was larger than the first!");
        }
 
    }
}
```

#### Orwell
```java
public class Orwell {
 
    public static void main(String[] args) {
        Scanner scan = new Scanner(System.in);
 
        // Write your program here
        System.out.println("Give a number:");
        int number = Integer.valueOf(scan.nextLine());
        if(number == 1984){
            System.out.println("Orwell");
        }
    }
}
```

#### Ancient
```java
public class Ancient {
 
    public static void main(String[] args) {
        Scanner scan = new Scanner(System.in);
 
        // Write your program here
        System.out.println("Give a year:");
        int date = Integer.valueOf(scan.nextLine());
        if(date < 2015){
            System.out.println("Ancient history!");
        }
    }
}
```

#### Positivity
```java
public class Positivity {
 
    public static void main(String[] args) {
        Scanner scan = new Scanner(System.in);
 
        // Write your program here
        System.out.println("Give a number:");
        int number = Integer.valueOf(scan.nextLine());
        if(number > 0){
            System.out.println("The number is positive.");
        }else{
            System.out.println("The number is not positive.");
        }
    }
}
```

#### Adulthood
```java
public class Adulthood {
 
    public static void main(String[] args) {
        Scanner scan = new Scanner(System.in);
 
        // Write your program here 
        System.out.println("How old are you?");
        int year = Integer.valueOf(scan.nextLine());
        if(year >= 18){
            System.out.println("You are an adult");
        }else{
            System.out.println("You are not an adult");
        }
    }
}
```

#### LargerThanOrEqualTo
```java
public class LargerThanOrEqualTo {
 
    public static void main(String[] args) {
        Scanner scan = new Scanner(System.in);
 
        System.out.println("Give the first number:");
        int number = Integer.valueOf(scan.nextLine());
        System.out.println("Give the second number:");
        int number2 = Integer.valueOf(scan.nextLine());
        if(number > number2){
            System.out.println("Greater number is: " + number);
        }else if(number < number2){
            System.out.println("Greater number is: " + number2);
        }else if(number == number2){
            System.out.println("The numbers are equal!");
        }
    }
}
```

#### GradesAndPoints
```java
public class GradesAndPoints {
 
    public static void main(String[] args) {
        Scanner scan = new Scanner(System.in);
 
        System.out.println("Give points [0-100]");
        int points = Integer.valueOf(scan.nextLine());
        if (points < 0) {
            System.out.println("Grade: impossible!");
        } else if (points >= 0 && points <= 49) {
            System.out.println("Grade: failed");
        } else if (points >= 50 && points <= 59) {
            System.out.println("Grade: 1");
        } else if (points >= 60 && points <= 69) {
            System.out.println("Grade: 2");
        } else if (points >= 70 && points <= 79) {
            System.out.println("Grade: 3");
        } else if (points >= 80 && points <= 89) {
            System.out.println("Grade: 4");
        } else if (points >= 90 && points <= 100) {
            System.out.println("Grade: 5");
        } else if (points > 100) {
            System.out.println("Grade: incredible!");
        }
 
    }
}
```

#### OddOrEven
```java
public class OddOrEven {
 
    public static void main(String[] args) {
        Scanner scan = new Scanner(System.in);
 
        // Write your program here 
        // HINT:
        // You can find out if a number is even or odd easily using the modulo operator %
        // Try the following commands to see what they print
        // System.out.println( 1%2 );
        // System.out.println( 2%2 );
        // System.out.println( 3%2 );
        // System.out.println( 4%2 );
        // System.out.println( 5%2 );
        // System.out.println( 6%2 );
        // System.out.println( 7%2 );
        // int luku = 8
        // System.out.println( luku%2 );
        // So, by taking the modulo of a number and two you can find out if it is even or odd !
        System.out.println("Give a number:");
        int number = Integer.valueOf(scan.nextLine());
        
        if(number % 2 == 0){
            System.out.println("Number " + number + " is even.");
        }else{
            System.out.println("Number " + number + " is odd.");
        }
    }
}
```

#### Password
```java
public class Password {
 
    public static void main(String[] args) {
        Scanner scan = new Scanner(System.in);
 
        // Write your program here 
        System.out.println("Password?");
        String input = scan.nextLine();
        
        if(input.equals("Caput Draconis")){
            System.out.println("Welcome!");
        }else{
            System.out.println("Off with you!");
        }
    }
}
```

#### Same
```java
public class Same {
 
    public static void main(String[] args) {
        Scanner scan = new Scanner(System.in);
 
        // Write your program here.
        System.out.println("Enter the first string:");
        String first = scan.nextLine();
        System.out.println("Enter the second string:");
        String second = scan.nextLine();
        if(first.equals(second)){
            System.out.println("Same");
        }else{
            System.out.println("Different");
        }
    }
}
```

#### CheckingTheAge
```java
public class CheckingTheAge {
 
    public static void main(String[] args) {
        Scanner scan = new Scanner(System.in);
        
        System.out.println("How old are you?");
        int year = Integer.valueOf(scan.nextLine());
        if(year >= 0 && year <= 120){
            System.out.println("OK");
        }else{
            System.out.println("Impossible!");
        }
    }
}
```

#### LeapYear
```java
public class LeapYear {
 
    public static void main(String[] args) {
        Scanner scan = new Scanner(System.in);
        
        System.out.println("Give a year:");
        int year = Integer.valueOf(scan.nextLine());
        
        if(year % 100 == 0 && year % 400 == 0){
            System.out.println("The year is a leap year.");
        }else if(year % 100 == 0 && year % 400 != 0){
            System.out.println("The year is not a leap year.");
        }else if(year % 4 == 0){
            System.out.println("The year is a leap year.");
        }else{
            System.out.println("The year is not a leap year.");
        }
    }
}
```

#### GiftTax
```java
public class GiftTax {
 
    public static void main(String[] args) {
        Scanner scan = new Scanner(System.in);
        
        System.out.println("Value of the gift?");
        int value = Integer.valueOf(scan.nextLine());
        
        if(value >= 5000 && value < 25000){
            System.out.println("Tax: " + (100 + (value - 5000) * 0.08));
        }else if(value >= 25000 && value < 55000){
            System.out.println("Tax: " + (1700 + (value - 25000) * 0.1));
        }else if(value >= 55000 && value < 200000){
            System.out.println("Tax: " + (4700 + (value - 55000) * 0.12));
        }else if(value >= 200000 && value < 1000000){
            System.out.println("Tax: " + (22100 + (value - 200000) * 0.15));
        }else if(value > 1000000){
            System.out.println("Tax: " + (142100 + (value - 1000000) * 0.17));
        }else{
            System.out.println("No tax!");
        }          
        
    }
}
```
