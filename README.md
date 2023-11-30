# cs305_Mod5_ZackMacMillan
#Fictional Project (public domain license)
## NFL score projector (java)
## Get started 
download a java platform (This example is for Java SE)
### install OPenJDK
run sudo apt update
run sudo apt install default-jdk
run sudo apt install default-jre

/this will allow you to run java based applications as well as developing and programming with java./

### java.util.Random

 // A Java program to demonstrate random number generation
// using java.util.Random;
import java.util.Random;

public class generateRandom{

	public static void main(String args[])
	{
		// create instance of Random class
		Random rand = new Random();

		// Generate random integers in range 0 to 999
		int rand_team1 = rand.nextInt(50);
		int rand_team2 = rand.nextInt(63);

		// Print random integers
		System.out.println("Random Integers: "+rand_team1);
		System.out.println("Random Integers: "+rand_team2);

	
	}
}

