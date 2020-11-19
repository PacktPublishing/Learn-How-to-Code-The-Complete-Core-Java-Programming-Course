package string_operations;

public class String_Replace {

	public static void main(String[] args) {
		
		/**
		 * Replace - Normal
		 * ReplaceAll - RegEx
		 */
		String str1 = "CONCENTRAT1234ON 1234MPROVES W1234TH PRACT1234CE";
		String str2 = "1234";
		String str3 = "I";
		
		System.out.println(str1.replace(str2, str3));
		
		String str4 = "EI#$T%HER #YO&*U CON#@$TR^O(L Y$O&U*R* #M%I^N^D O^R& I&*(T W&I(*)L%L ()C^O#N%T&R@$%@OL @Y$O$U%";
		String patt = "[^A-Za-z0-9\\s]";
		
		System.out.println(str4.replaceAll(patt, ""));
	}

}
