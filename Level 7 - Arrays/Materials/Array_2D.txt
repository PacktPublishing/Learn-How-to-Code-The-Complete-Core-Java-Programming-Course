package arrays;

public class Array_2D {

	public static void main(String[] args) {
		
		/*
		 * What is 2-D Array?
		 * How to get length of 2-D Array?
		 * How to add elements to 2-D Array?
		 * How to retrieve elements from 2-D Array?
		 * How to update elements of 2-D Array?
		 * How to iterate over 2-D Array using modified 'for loop'?
		 */
		
		String [][] arr = 
				{
				{"A","B","C"},
				{"E","F"},
				{"SDF","FG","FG","JH"}
				};			
		
		System.out.println(arr.length);
		System.out.println(arr[2].length);
		
		System.out.println(arr[2][1]);
		arr[2][1] = "AAAA";
		System.out.println(arr[2][1]);
		
		for(String[] x : arr) {
			for(String y : x) {
				System.out.println(y);
			}
			System.out.println("----------------------");
		}
		
	}

}
