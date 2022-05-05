package arrays;

public class Array_Of_Object {

	public static void main(String[] args) {
		
		Object [][] arr = 
				{
				{"Mayur", 33, 5.11, 'M'},
				{"Shruti", 30, 5.7, 'F'},
				{"Gaurav", 31, 5.10, 'M'},
				{"John", 45, 6.1, 'M'}
				};
		
		
		for (Object [] x : arr) {
			for (Object y : x) {
				System.out.print(y + " ");
			}
			System.out.print("\n");
		}

	}

}
