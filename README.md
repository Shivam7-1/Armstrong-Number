# Armstrong-Number
Code of armstrong number
package armstrongNumbers;
import java.util.Scanner;
public class Armstrongnumbers {

	public static void main(String[] args) {
		 int c=0,a,temp;  
		 Scanner Sc= new Scanner(System.in);
		    int n=Sc.nextInt();//It is the number to check armstrong  
		    temp=n;  
		    while(n>0)  
		    {  
		    a=n%10;  
		    n=n/10;  
		    c=c+(a*a*a);  
		    }  
		    if(temp==c)  
		    System.out.println("armstrong number");   
		    else  
		        System.out.println("Not armstrong number");   
		   }  
		}  
	
