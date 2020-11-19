package oops_concepts;

public class Method_Overloading {
	
	/**
	 * Method Overloading
	 * Data Type
	 * Number of Args
	 * Order
	 * 
	 */
	
	public void addition(int num1, int num2) {
		System.out.println(num1 + num2);
	}
	
	public void addition(double num1, double num2) {
		System.out.println(num1 + num2);
	}
	
	public void addition(int num1, double num2) {
		System.out.println(num1 + num2);
	}
	
	public void addition(double num1, int num2) {
		System.out.println(num1 + num2);
	}
	
	public void addition(int num1, int num2, int num3) {
		System.out.println(num1 + num2 + num3);
	}
	
}
