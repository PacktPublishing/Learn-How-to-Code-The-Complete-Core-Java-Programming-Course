package exceptions;

public class Intro {

	public static void main(String[] args) {
		
		/*
		 * 1. What is an Exception?
		 * 	  Exceptions are events which occur during the execution of 
		 *    programs that disrupt the normal flow of the application.
		 *    e.g. String Index Out Of Boundaries, Dividing by Zero, Null Pointer 
		 *    
		 * 2. What is Exception Object?
		 * 	  An exception object is an instance of an exception class. It gets 
		 * 	  created and handed over to the Java runtime when an exceptional event 
		 * 	  occurs. 
		 * 	  Exception Object contains:
		 * 		a) Information about the error
		 *		b) The state of the program
		 *
		 */
		
		String x = null;
		
		System.out.println(100/0);
		
		System.out.println("Hello World");

	}

}
