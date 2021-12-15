
import java.util.Arrays;
import java.util.Scanner;
public class Calculator {
public static void main(String[] args){
    Scanner in = new Scanner(System.in);
    
String answer;
    do{
    int [] myArray = new int[5];
    
    System.out.print("Enter five numbers: ");
    for (int i = 0; i < myArray.length; i++){
        while(in.hasNextInt() == false){
            System.out.println("Wrong!! TRY AGAIN!");
            in.next();
        }
        myArray[i] = in.nextInt();
    }
 
    System.out.print("Enter number for an operation (1) for Squareroot, (2) for Power, (3) for DivBy5and6, (4) for Increment: ");
    int operation = in.nextInt();
    
    switch (operation){
        case 1 : Squareroot(myArray);break;
             case 2 : Power(myArray);break;
                  case 3 :  DivBy5and6(myArray);break;
                     case 4 :  System.out.println("The Increment for an array is: " + Arrays.toString(Increment(myArray)));break;
    }
    
    System.out.println("Want to rerun the program again? (Y or N) ");
    answer=in.next();
            }while(answer.equalsIgnoreCase("y"));
    
}

public static void Squareroot(int[] array){
    int[] squareroot = new int[array.length];
                
    for (int i = 0; i<squareroot.length; i++){
    squareroot[i] = (int) Math.sqrt(array[i]); 
    System.out.println("The squareroot for " + array[i] + " is " + squareroot[i]);
    }
}

public static void Power(int[] array){
    int[] Power = new int[array.length];
                
    for (int i = 0; i<Power.length; i++){
    Power[i] = (int) Math.pow(array[i],2); 
    System.out.println("The power for " + array[i] + " is " + Power[i]);
    }
}

public static void DivBy5and6(int[] array){
                
    for (int i = 0; i<array.length; i++){
    if (array[i] % 5 != 0 && array[i] % 6 != 0)continue;
    System.out.print(array[i] + "  ");
    }
}

public static int[] Increment(int[] array){
     int[] Increment = new int[array.length];

     for (int i = 0; i<array.length; i++){
    Increment[i] =  array[i]+1;
    }
    return Increment;
}
}
