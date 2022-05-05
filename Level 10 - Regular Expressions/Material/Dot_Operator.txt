package regex;

public class Dot_Operator {

	public static void main(String[] args) {
		
		/*
		 * (DOT) '.' -> Matches Any Single Character
		 */
		
		String patt = "ABC.";
		
		String str1 = "ABC9";
		
		String patt1 = "ABC.*";
		
		String str2 = "ABC^&*IJHG987";
		
		System.out.println(str2.matches(patt1));
		
		
		
		
		
		

	}

}
