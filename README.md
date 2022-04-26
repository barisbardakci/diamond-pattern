# diamond-pattern
Java101_22 this program makes a diamond pattern with star by given number of rows

https://www.patika.dev/tr

import java.util.Scanner;
public class Main
{
	public static void main(String[] args) {
	    int i, j, k, row;
	    
	    Scanner input=new Scanner(System.in);
	    System.out.print("Number of rows : ");
	    row=input.nextInt();
	    
	    for(i=1; i<=row; i++){
	        for(j=1; j<=row-i; j++){
	            System.out.print(" ");
	        }
	        for(k=1; k<=(2*i)-1; k++){
	            System.out.print("*");
	        }
	        System.out.println("");
	    }
	    for(i=row-1; 0<=i; i--){
	        for(j=1; j<=row-i; j++){
	            System.out.print(" ");
	        }
	        for(k=1; k<=(2*i)-1; k++){
	            System.out.print("*");
	        }
	        System.out.println("");
	        
	    }
	    
	}
}
