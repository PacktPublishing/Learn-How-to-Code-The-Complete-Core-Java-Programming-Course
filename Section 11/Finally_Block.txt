package exceptions;

public class Finally_Block {

	public static void main(String[] args) {
		
		/*
		 * The finally block gets executed after successful run of the 
		 * try block or after one of the catch blocks handled an exception
		 */

		int num1 = 100;
		int num2 = 10;
		
		try {
			int num3 = num1 / num2;
		}  finally {
			System.out.println("Finally Block Code");
		}
	}

}
