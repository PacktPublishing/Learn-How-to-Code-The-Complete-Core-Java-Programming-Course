package date_time;

import java.time.LocalDate;
import java.time.temporal.ChronoUnit;

public class Date_Add_Subtract {

	public static void main(String[] args) {
		
		/*
		 * 1. Plus / Minus Methods
		 * 2. ChronoUnit
		 */
		
		LocalDate d1 = LocalDate.now().plus(10, ChronoUnit.DECADES);
		
		System.out.println(d1);
		

	}

}
