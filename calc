import java.util.Scanner;
public class SimleCalculator{
  public static void main(String[] args) {
    Scanner scan = new Scanner(System.in);
    int firstNumber;
    int secondNumber;
    char operator;
    System.out.println("Write a number");
    firstNumber = scan.nextInt();
    System.out.println("Write another number");
    secondNumber = scan.nextint();
    System.out.println("write operation");
    c=scan.next().charAt(0);
    switch(c) {
    case '+': Add(firstNumber, secondNumber);
            break;
    case '-':Sub(firstNumber, secondNumber);
            break;
    case '*': Mult(firstNumber, secondNumber);
            break;
    case '/': div(firstNumber,secondNumber);
            break;
    default:
           System.out.printf("You have entered wrong operator");
                }
  }
    static void Add( int firstNumber, int secondNumber ) {
        System.out.println("Addition = " + (firstNumber + secondNumber));
    }
    static void Sub( int firstNumber, int secondNumber ) {
        System.out.println("Substratcion = " + (firstNumber - secondNumber));
    }
    static void Mul( int firstNumber, int secondNumber ) {
        System.out.println("Multiplication = " + (firstNumber * secondNumber));
    }
    static void div( int firstNumber, int secondNumber) {
        System.out.println("Division= "+(firstNumber / secondNumber));
    }
}
