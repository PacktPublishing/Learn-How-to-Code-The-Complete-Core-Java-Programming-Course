package date_time;

import java.time.LocalDate;
import java.time.format.DateTimeFormatter;

public class DateTime_Formatter {

	public static void main(String[] args) {
		
		/*
		 * yyyy - YEAR
		 * yy - YEAR
		 * MM - MONTH
		 * MMM - MONTH
		 * dd - DAY
		 */
		
		String str1 = "24/04/86";
		
		DateTimeFormatter formatter = DateTimeFormatter.ofPattern("[MM-dd-yyyy][MMM-dd-yyyy][dd/MM/yy]");
		
		LocalDate d1 = LocalDate.parse(str1,formatter);
		
		System.out.println(d1);
		
		
		
	}

}
