package exceptions;

import java.io.FileInputStream;

public class CheckedVsUnchecked {

	public static void main(String[] args) {
		
		/*
		 * Checked Exceptions : Checked at Compile-Time
		 * e.g. IOException, SQLException, ClassNotFoundException etc.
		 * 
		 * Unchecked Exceptions (RunTime Exceptions): Checked at Run-Time
		 * e.g. ArithmeticException, ArrayIndexOutOfBoundsException etc.
		 */
		
		//FileInputStream x = new FileInputStream("Users⁩/md/⁨Downloads⁩/abc.txt");
		
		System.out.println(100/0);
		 
		 
	}

}
