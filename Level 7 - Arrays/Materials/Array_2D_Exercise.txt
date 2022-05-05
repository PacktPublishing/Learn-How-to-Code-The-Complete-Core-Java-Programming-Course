package arrays;

public class Array_2D_Exercise {

	public static void main(String[] args) {
		
		/*
		 * Write a program to add table to 2 to 6 in the rows of a 2-D array
		 * {
		 * 	{2,4,6,8...20},
		 * 	{3,6,9,12...30},
		 * 	{4,8,12,16...40},
		 * 	{5,10,15,20...50},
		 * 	{6,12,18,24...60}
		 * }
		 */
		
		int [][] arr = new int [5][10];
		
		for(int i = 2; i <= 6; i++) {
			for(int j = 1; j <= 10; j++) {
				arr[i-2][j-1] = i * j;
			}
		}
		
		for(int [] x : arr) {
			for(int y : x) {
				System.out.print(y + " ");
			}
			System.out.print("\n");
		}

	}

}
