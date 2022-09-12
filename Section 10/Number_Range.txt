package regex;

public class Number_Range {

	public static void main(String[] args) {
		
		/*
		 * Create a RegEx pattern to represent following number ranges
		 * 1. 0-99
		 * 2. 0-1000
		 * 3. 99-9999
		 * 4. 25-75
		 * 5. 220-240
		 */
		
		String patt = "2[2-3][0-9]|240";
		
		String str1 = "100";
		
		System.out.println(str1.matches(patt));
		
	}

}
