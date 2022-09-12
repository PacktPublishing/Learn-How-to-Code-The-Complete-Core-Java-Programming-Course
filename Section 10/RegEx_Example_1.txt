package regex;

public class RegEx_Example_1 {

	public static void main(String[] args) {
		
		/*
		 * Create a RegEx pattern to represent following web sites
		 * 1. www.dezlearn.com
		 * 3. www.dezlearn.us
		 * 2. www.dez.com
		 * 3. www.dez.us
		 */
		String patt = "www\\.(dezlearn|dez)\\.(com|us)";
		String str1 = "www.dez.com";
		
		System.out.println(str1.matches(patt));
		
	}

}
