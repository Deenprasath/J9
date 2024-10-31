import java.util.Scanner;
public class Main
{
	public static void main(String[] args) {
		Scanner sc = new Scanner (System.in);
	    System.out.println("ente the num:");
	    int num = sc.nextInt();
	    Boolean isprime = true;
	    if (num<= 1)
	    {
	        isprime = false;
	        
	    }
		else{
		    for(int = 2; i<= Math.sqet(num); i++)
		    {
		        if(num % i == 0)
		        {
		            isprime = false;
		            break;
		        }
		    }
		}
	if(isPrime) {
            System.out.println(num + " is a prime number.");
        } else {
            System.out.println(num + " is not a prime number.");
        }
		
}
}
