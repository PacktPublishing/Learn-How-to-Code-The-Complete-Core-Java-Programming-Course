package exceptions;

import java.io.FileInputStream;
import java.io.FileNotFoundException;
import java.io.IOException;

public class Throws_Declaration {

	public static void main(String[] args) throws IOException {
		
		abc();
	}
	
	public static void abc() throws IOException {
		FileInputStream x = new FileInputStream("Users⁩/md/⁨Downloads⁩/abc.txt");
	}
}
