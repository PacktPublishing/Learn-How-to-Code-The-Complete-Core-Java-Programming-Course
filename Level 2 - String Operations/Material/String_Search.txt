package string_operations;

public class String_Search {

	public static void main(String[] args) {
		
		/**
		 * Contains
		 * Starts with
		 * Ends with
		 * Index of
		 * Last Index of
		 */
		
		String str1 = "I love Java love and Selenium";
		
		String str2 = "java";
		
		System.out.println(str1.toLowerCase().contains(str2.toLowerCase()));
		
		System.out.println(str1.startsWith("I"));
		
		System.out.println(str1.endsWith("Selenium1"));
		
		System.out.println(str1.indexOf("love"));
		
		System.out.println(str1.indexOf("love", 6));
		
		System.out.println(str1.lastIndexOf("love"));
		
		
	}

}
