package regex;

public class Quantifiers {

	public static void main(String[] args) {
		
		/*
		 * 1. * - Matches 0 or more instances of preceding character
		 * 2. + - Matches 1 or more instances of preceding character
		 * 3. ? - Matches 0 or 1 instances of preceding character
		 * 4. {n} - Matches exactly 'n' number instances of preceding character
		 * 5. {n,m} - Matches minimum 'n' or maximum 'm' instances of preceding character
		 * 6. {n,} - Matches minimum 'n' or more instances of preceding character
		 */
		
		String patt = "ab(xyz){2,}";
		
		String str1 = "abxyzxyzxyzxyzxyzxyz";
		
		System.out.println(str1.matches(patt));
		
	}

}
