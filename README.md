# forLoopsEvenNumberPrint
Print all even number util user input using for loop
package mypackage;

import java.util.Scanner;

public class PrintEven {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		System.out.print("Enter number:");
      Scanner input=new Scanner(System.in);
      int n=input.nextInt();
     // int i=0;
      //while(i<=n) {
    	  //i++;
    	  //if(i%2==0) {
    		  //System.out.println(i);
    	  //}
      for(int i=2;i<=n;i++) {
    	  if(i%2==0) {
    		  System.out.println(i);
    	  }//else {
    		  //System.out.println();
    	 // }
      }
	}

}
