package arrays;

public class Array_Object {

	public static void main(String[] args) {
		
		int [] arr1 = new int [10];
		
		arr1[0] = 20;
		arr1[1] = 40;
		arr1[3] = 60;
		arr1[2] = 80;
		arr1[6] = 100;
		
		for(int i = 0; i <= arr1.length-1; i++) {
			System.out.println(arr1[i]);
		}

	}

}
