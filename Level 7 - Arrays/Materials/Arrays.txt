package arrays;

public class Arrays {

	public static void main(String[] args) {
		
		/*
		 * What is an array?
		 * How to declare an array?
		 * What is length of array?
		 * How to update array elements?
		 * Iterating on array elements using For Loop.
		 */
		
		String [] DaysOfWeek = {"Mon", "Tue", "Wed", "Thu", "Fri", "Sat", "Sun"};
		
		System.out.println(DaysOfWeek.length);
		
		System.out.println(DaysOfWeek[2]);
		
		DaysOfWeek[2] = "RRR";
		
		System.out.println(DaysOfWeek[2]);
		
		for (int i = 0; i <= DaysOfWeek.length - 1; i++) {
			System.out.println(DaysOfWeek[i]);
		}
		
		int [] arr1 = {12,3,34,65,765,678,87654,456};
		
		char [] arr2 = {'a','e','i'};
		
		
	}

}
