package string_operations;

public class String_Basics {

	public static void main(String[] args) {
		
		/**
		 * Concatenate 
		 * Length
		 * Trim
		 * Upper Case
		 * Lower Case
		 * Empty
		 */
		
		String str1 = "De Zinnia";
		String str2 = " Institutes";
		
		String str3 = str1 + str2;
		System.out.println(str3);
		
		String str4 = str1.concat(str2);
		System.out.println(str4);
		
		int num1 = 100;
		
		System.out.println(str1 + num1);
		
		System.out.println(str1.length());
		
		String str5 = "    LYUUxfcgvhbjknl TYHJ cbhjnkl hvjbkn     ";
		
		System.out.println(str5);
		
		System.out.println(str5.trim());
		
		System.out.println(str5.toUpperCase());
		
		System.out.println(str5.toLowerCase());
		
		System.out.println(str5.isEmpty());
		
		String str6 = "";
		
		System.out.println(str6.isEmpty());
		
	}

}
