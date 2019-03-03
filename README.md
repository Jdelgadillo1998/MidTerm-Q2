# MidTerm-Q2
import java.util.*;


public class minMax {

	public static void main(String[] args) {

		minAndMax();

	}

	public static void minAndMax() {
		Scanner length = new Scanner(System.in);
		Scanner input = new Scanner(System.in);

		System.out.println("What is the array size: ");

		int len=length.nextInt();
		int[] numbers = new int[len];

		for (int i = 0; i < numbers.length; i++)
		{
			System.out.println("Please enter number");

			numbers[i] = input.nextInt();

		}

		System.out.println("Minimum = " + numbers[0]);
		System.out.println("Maximum = " + numbers[numbers.length-1]);
	}

}
