import java.io.*;
import java.util.*;
  public class Calc{
    public static void main(String args[]){
      Scanner sc=new Scanner(System.in);
      System.out.println("Enter the Inputs");
      int num1=sc.nextInt();
      char in=sc.next().charAt(0);
      int num2=sc.nextInt();
      if(in=='/'){
      System.out.println("ANS:"+(num1/num2));
      }
      else if(in=='%')
      {
      System.out.println("ANS:"+(num1%num2));
      }
      else
      {
      System.out.println("INVALID");
      }
    }
  }  
        
