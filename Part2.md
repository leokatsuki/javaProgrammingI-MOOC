# Java Programming I - University of Helsinki MOOC

## Exercises Part 2

#### Squared
```java
public class Squared {
 
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
 
        int number = Integer.valueOf(scanner.nextLine());
        
        int square = number * number;
        
        System.out.println(square);
        
        
    }
}
```

#### SquareRootOfSum
```java
public class SquareRootOfSum {
 
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
 
        int first = Integer.valueOf(scanner.nextLine());
        int second = Integer.valueOf(scanner.nextLine());
        
        int sum = first + second;
        double squareRoot = Math.sqrt(sum);
        System.out.println(squareRoot);
    }
}
```

#### AbsoluteValue
```java
public class AbsoluteValue {
 
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
 
        int number = Integer.valueOf(scanner.nextLine());
        
        if(number < 0){
            int mul = number * -1;
            System.out.println(mul);
        }else{
            System.out.println(number);
        }
    }
}
```

#### ComparingNumbers
```java
public class ComparingNumbers {
 
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        
        int first = Integer.valueOf(scanner.nextLine());
        int second = Integer.valueOf(scanner.nextLine());
        
        if(first > second){
            System.out.println(first + " is greater than " + second);
        }else if(first < second){
            System.out.println(first + " is smaller than " + second);
        }else{
            System.out.println(first + " is equal to " + second);
        }
    }
}
```

#### CarryOn
```java
public class CarryOn {
 
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        
        while(true){
            System.out.println("Shall we carry on?");
            String res = scanner.nextLine();
            if(res.equals("no")){
                break;
            }
        }
 
    }
}
```

#### AreWeThereYet
```java
public class AreWeThereYet {
 
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        
        
        while(true){
            System.out.println("Give a number:");
            int number = Integer.valueOf(scanner.nextLine());
            
            if(number == 4){
                break;
            }
        }
    }
}
```

#### OnlyPositives
```java
public class OnlyPositives {
 
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
 
        
        while(true){
            System.out.println("Give a number:");
            int number = Integer.valueOf(scanner.nextLine());
            
            if(number<0){
                System.out.println("Unsuitable number");
                continue;
            }else if(number == 0){
                break;
            }else{
                System.out.println(number * number);
            }
        }
    }
}
```

#### NumberOfNumbers
```java
public class NumberOfNumbers {
 
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        
        int times = 0;
 
        while(true){
            System.out.println("Give a number:");
            
            int number = Integer.valueOf(scanner.nextLine());     
       
            if(number == 0){
                break;      
            }else{
                times = times + 1;
            }
        }
        
        System.out.println("Number of numbers: " + times);
    }
}
```

#### NumberOfNegativeNumbers
```java
public class NumberOfNegativeNumbers {
 
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        
        int times = 0;
 
        while(true){
            System.out.println("Give a number: ");
            int number = Integer.valueOf(scanner.nextLine());
            
            if(number == 0){
                break;
            }
            
            if(number < 0){
                times = times + 1;
            }
        }
        
        System.out.println("Number of negative numbers: " + times);
    }
}
```

#### SumOfNumbers
```java
public class SumOfNumbers {
 
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        
        int sum = 0;
 
        while(true){
            System.out.println("Give a number:");
            
            int number = Integer.valueOf(scanner.nextLine());
            
            if(number == 0){
                break;
            }else{
                sum += number;
            }
        }
        
        System.out.println("Sum of the numbers: " + sum);
    }
}
```

#### NumberAndSumOfNumbers
```java
public class NumberAndSumOfNumbers {
 
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
 
        int times = 0;
        int sum = 0;
        
        while(true){
            System.out.println("Give a number:");
            
            int number = Integer.valueOf(scanner.nextLine());
            
            if(number == 0){
                break;
            }else{
                times = times + 1;
                sum = sum + number;
            }
        }
        
        System.out.println("Number of numbers: " + times);
        System.out.println("Sum of the numbers: " + sum);
    }
}
```

#### AverageOfNumbers
```java
public class AverageOfNumbers {
 
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
 
        int sum = 0;
        int times = 0;
        
        while(true){
            System.out.println("Give a number: ");
            
            int number = Integer.valueOf(scanner.nextLine());
            
            if(number == 0){
                break;
            }else{
                sum += number;
                times += 1;
                
            }
        }
        
        float avg = (float) sum/times;
        System.out.println("Soma: " + sum);
        System.out.println("Times: " + times);
        System.out.println("Average of the numbers: " + avg);
    }
}
```

#### AverageOfPositiveNumbers
```java
public class AverageOfPositiveNumbers {
 
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        
        int sum = 0;
        int times = 0;
        
 
        while(true){
            int number = Integer.valueOf(scanner.nextLine());
            
            if(number == 0){               
                break;
            }else if(number > 0){
                sum += number;
                times += 1;
            }  
        }
        float avg = (float) sum/times;
        
        if(sum == 0){
            System.out.println("Cannot calculate the average");
        }else{
            System.out.println(avg);
        }
    }
}
```

#### Counting
```java
public class Counting {
 
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
   
        int number = Integer.valueOf(scanner.nextLine()); 
        
        for(int i=0; i<=number; i++){
            System.out.println(i);
        }
    }
}
```

#### CountingToHundred
```java
public class CountingToHundred {
 
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
 
        int number = Integer.valueOf(scanner.nextLine());
        
        for(int i=number; i<=100; i++){
            System.out.println(i);
        }
             
    }
}
```

#### FromWhereToWhere
```java
public class FromWhereToWhere {
 
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        
        System.out.println("Where to? ");
        int firstNumber = Integer.valueOf(scanner.nextLine());
        System.out.println("Where from?");
        int secondNumber = Integer.valueOf(scanner.nextLine());
        
        for(int i=secondNumber; i<=firstNumber; i++){
            System.out.println(i);
        }
    }
}
```

#### SumOfASequence
```java
public class SumOfASequence {
 
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
 
        int number = Integer.valueOf(scanner.nextLine());
        int sum = 0;
        for(int i=1; i <= number; i++){
            sum += i; 
        }
        System.out.println("The sum is " + sum);
    }
}
```

#### SumOfASequenceTheSequel
```java
public class SumOfASequenceTheSequel {
 
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        
        int sum = 0;
        
        System.out.println("First number?");
        int firstNumber = Integer.valueOf(scanner.nextLine());
        System.out.println("Second number?");
        int secondNumber = Integer.valueOf(scanner.nextLine());
        
        for(int i=firstNumber; i<=secondNumber; i++){
            sum += i;
        }
        
        System.out.println("The sum is " + sum);
 
    }
}
```

#### Factorial
```java
public class Factorial {
 
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
 
        System.out.println("Give a number:");
        int number = Integer.valueOf(scanner.nextLine());
        int mul = 1;
        
        for(int i=1; i<=number; i++){
            mul *= i;
        }
        
        System.out.println("Factorial: " + mul);
    }
}
```

#### RepeatingBreakingAndRemembering
```java
public class RepeatingBreakingAndRemembering {
 
    public static void main(String[] args) {
        
        // This exercise is worth five exercise points, and it is 
        // gradually extended part by part.
        
        // If you want, you can send this exercise to the server
        // when it's just partially done. In that case the server will complain about 
        // the parts you haven't done, but you'll get points for the finished parts.
        
        Scanner scanner = new Scanner(System.in);
 
        System.out.println("Give numbers:");
        int sum = 0;
        int count = 0;
        int evenCount = 0;
        int oddCount = 0;
        while (true) {
            int number = Integer.valueOf(scanner.nextLine());
            if (number == -1) {
                System.out.println("Thx! Bye!");
                break;
            } else {
                sum += number;
                count++;
                if (number % 2 == 0) {
                    evenCount++;
                } else {
                    oddCount++;
                }
            }
        }
        
        float avg = (float) sum/count;
        
        System.out.println("Sum: " + sum);
        System.out.println("Numbers: " + count);
        System.out.println("Average: " + avg);
        System.out.println("Even: " + evenCount);
        System.out.println("Odd: " + oddCount);
    }
}
```

#### InAHoleInTheGround
```java
public class InAHoleInTheGround {
 
    public static void main(String[] args) {
        printText();
    }
    
    public static void printText() {
        // Write some code in here
        System.out.println("In a hole in the ground there lived a method");
    }
}
```

#### Reprint
```java
public class Reprint {
 
    public static void main(String[] args) {
        // ask the user for how many times should the text be printed
        // then call the printText-method multiple times with a while-loop
        
        Scanner scanner = new Scanner(System.in);
        System.out.println("How many times?");
        int number = Integer.valueOf(scanner.nextLine());
        
        for(int i=1; i<=number; i++){
            printText();
        }
        
    }
    
    // Don't change the next line that defines the method!
    // (We aren't giving a method a parameter yet)
    public static void printText() {
        // write some code here
        System.out.println("In a hole in the ground there lived a method");
    }
}
```

#### FromOneToParameter
```java
public class FromOneToParameter {
 
    public static void main(String[] args) {
        printUntilNumber(5);
    }
    public static void printUntilNumber(int number){
        int i=1;
        while(i <= number){
            System.out.println(i);
            i++;
        }
    }
}
```

#### FromParameterToOne
```java
public class FromParameterToOne {
 
    public static void main(String[] args) {
        printFromNumberToOne(5);
 
    }
    
    public static void printFromNumberToOne(int number){
        int i = number;
        while (i != 0){
            System.out.println(i);
            i--;
        }
    }
 
}
```

#### Division
```java
public class Division {
 
    public static void main(String[] args) {
        
        // Once you have implemented the division method, you can
        // try it out here. Fopr example division(3,5);
        // should print "0.6"
 
        division(3, 5);
    }
 
    // implement the method here
    public static void division(int firstNumber, int secondNumber){
        float div = (float) firstNumber/secondNumber;
        System.out.println(div);
    }
}
```

#### DivisibleByThree
```java
public class DivisibleByThree {
 
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
 
    }
 
    public static void divisibleByThreeInRange(int beginning, int end){
        for(int i=beginning; i<=end ;i++){
            if(i % 3 == 0){
                System.out.println(i);
            }
        }
    }
}
```

#### NumberUno
```java
public class NumberUno {
 
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        numberUno();
    }
    
    public static int numberUno(){
        return 1;
    }
 
}
```

#### Word
```java
public class Word {
 
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        word();
    }
 
    public static String word(){
        return "Hello world!";
    }
}
```

#### Summation
```java
public class Summation {
 
    public static int sum(int num1, int num2, int num3, int num4) {
        // write some code here
        int soma = num1 + num2 + num3 + num4;
        return soma;
    }
 
    public static void main(String[] args) {
        int result = sum(4, 3, 6, 1);
        System.out.println("Sum: " + result);
    }
}
```

#### Smallest
```java
public class Smallest {
 
    public static int smallest(int number1, int number2) {
        // Write some code here
        // don't print anything inside this method
        // there must be a return in the end of the method
        if(number1 < number2){
            return number1;
        }else{
            return number2;
        }
    }
 
    public static void main(String[] args) {
        int result = smallest(2, 7);
        System.out.println("Smallest: " + result);
    }
}
```

#### Greatest
```java
public class Greatest {
 
    public static int greatest(int number1, int number2, int number3) {
        //write some code here
        if(number1 > number2 && number1 > number3){
            return number1;
        }else if(number2 > number1 && number2 > number3){
            return number2;
        }else{
            return number3;
        }
    }
 
    public static void main(String[] args) {
        int result = greatest(2, 7, 3);
        System.out.println("Greatest: " + result);
    }
}
```

#### Averaging
```java
public class Averaging {
 
    // implement the sum method here again
    public static int sum(int number1, int number2, int number3, int number4) {
        int soma = number1 + number2 + number3 + number4;
        return soma;
    }
 
    public static double average(int number1, int number2, int number3, int number4) {
        float avg = (float) sum(number1, number2, number3, number4) / 4;
        return avg;
    }
 
    public static void main(String[] args) {
        double result = average(4, 3, 6, 1);
        System.out.println("Average: " + result);
    }
}
```

#### StarSign
```java
public class StarSign {
 
    public static void main(String[] args) {
 
        
        //The tests are not checking the main, so you can modify it freely.
        //NB: If the tests don't seem to pass, you should try the methods here
        //in the main to make sure they print the correct shapes!
        
        printStars(3);
        System.out.println("\n---");  // printing --- between the shapes
        printSquare(4);
        System.out.println("\n---");
        printRectangle(5, 6);
        System.out.println("\n---");
        printTriangle(3);
        System.out.println("\n---");
    }
 
    public static void printStars(int number) {
        // first part of the exercise
        for(int i=0; i<number; i++){
            System.out.print("*");
        }
        System.out.println("");
    }
 
    public static void printSquare(int size) {
        // second part of the exercise
        for(int i=0; i<size; i++){
            printStars(size);
        }
    }
 
    public static void printRectangle(int width, int height) {
        // third part of the exercise
        for(int i=0; i<height; i++){
            printStars(width);
        }
    }
 
    public static void printTriangle(int size) {
        // fourth part of the exercise
        for(int i=1; i<=size; i++){
            printStars(i);
        }
    }
}
```

#### AdvancedAstrology
```java
public class AdvancedAstrology {
 
    public static void printStars(int number) {
        // part 1 of the exercise
        for(int i=0; i<number; i++){
            System.out.print("*");
        }
        System.out.println("");
    }
 
    public static void printSpaces(int number) {
        // part 1 of the exercise
        for(int i=0; i<number; i++){
            System.out.print(" ");
        }
    }
 
    public static void printTriangle(int size) {
        // part 2 of the exercise
        for(int i=1; i<=size; i++){
            printSpaces(size-i);
            printStars(i);
        }
    }
 
    public static void christmasTree(int height) {
        // part 3 of the exercise
        for(int i=1; i<=height; i++){
            printSpaces(height-i);
            printStars(2*i-1);
        }
        for(int j=0; j<2; j++){
            printSpaces(height-2);
            printStars(3);
        }
    }
 
    public static void main(String[] args) {
        // The tests are not checking the main, so you can modify it freely.
        
        printTriangle(5);
        System.out.println("---");
        christmasTree(4);
        System.out.println("---");
        christmasTree(10);
    }
}
```
