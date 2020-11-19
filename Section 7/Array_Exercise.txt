package arrays;

public class Array_Exercise {

	public static void main(String[] args) {
		
		/*
		 * Write a program to reverse the contents of an array
		 */
	
		int [] arr = {10,20,30,35,40,50,60};
		
		int j = arr.length-1;
		int temp = 0;
		
		for(int i = 0; i <= (arr.length-1)/2; i++) {
			temp = arr[i];
			arr[i] = arr[j];
			arr[j] = temp;
			j--;
		}
		
		for(int x : arr) {
			System.out.println(x);
		}
		
		
	}
}
