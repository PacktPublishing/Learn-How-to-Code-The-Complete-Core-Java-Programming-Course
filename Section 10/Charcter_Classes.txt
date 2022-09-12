package regex;

public class Charcter_Classes {

	public static void main(String[] args) {
		
		/*
		 * 1. \d - matches a single digit character
		 * 2. \w - matches a single word character
		 * 3. \s - matches a single whitespace character
		 * 4. \D - matches a single non-digit character
		 * 5. \W - matches a single non-digit and non-word character
		 */
		
		
		String patt = "\\w{2,6}\\W{2}";
		
		String str1 = "rtTYUIOY*(";
		
		System.out.println(str1.matches(patt));
		
	}

}
