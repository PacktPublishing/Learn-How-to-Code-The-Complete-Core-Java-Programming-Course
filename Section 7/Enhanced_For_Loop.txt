package arrays;

import java.util.Scanner;

public class Enhanced_For_Loop {

	public static void main(String[] args) {
		
		/*
		 * Create a program to add table of any given number to an array.
		 * Create an enhanced for loop to display all the contents of the array
		 */
		
		Scanner s1 = new Scanner(System.in);
		
		System.out.println("Please enter a number:");
		
		int num1 = s1.nextInt();
		
		int [] arr = new int [10];
		
		for (int i = 1; i <= 10; i++) {
			arr[i-1] = num1 * i;
		}
		
		System.out.println("-------------------");
		
		for(int n : arr) {
			System.out.println(n);
		}
		
		
	}

}
