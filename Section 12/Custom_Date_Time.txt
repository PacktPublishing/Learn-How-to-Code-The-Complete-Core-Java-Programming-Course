package date_time;

import java.time.LocalDate;
import java.time.LocalDateTime;
import java.time.LocalTime;
import java.time.Month;

public class Custom_Date_Time {

	public static void main(String[] args) {
		
		LocalDate d1 = LocalDate.of(2020, 12, 31);
		
		LocalDate d2 = LocalDate.of(2020, Month.DECEMBER, 31);
		
		System.out.println(d1);
		System.out.println(d2);
		
		LocalTime t1 = LocalTime.of(20, 45);
		LocalTime t2 = LocalTime.of(15, 30, 20);
		LocalTime t3 = LocalTime.of(12, 15, 24, 123);
		
		System.out.println(t1);
		System.out.println(t2);
		System.out.println(t3);
		
		LocalDateTime dt1 = LocalDateTime.of(d2, t2);
		LocalDateTime dt2 = LocalDateTime.of(2022, 06, 24, 12, 30, 45, 333);
		
		System.out.println(dt1);
		System.out.println(dt2);
		

	}

}
