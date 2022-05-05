package regex;

import java.util.regex.Matcher;
import java.util.regex.Pattern;

public class GreedyAndLazyMatch {

	public static void main(String[] args) {
		
		/*
		 * * - Greedy	*? - Non Greedy
		 * + - Greedy	+? - Non Greedy
		 * {} - Greedy	{}? - Non Greedy
		 */
		
		String str1 = "XXfdugshYYyfuwgXXytufgh678ijYYgusdfhXXwwuygriehkYYdhjgkfd";
		
		String patt = "XX.*?YY";
		
		Pattern p = Pattern.compile(patt);
		
		Matcher m = p.matcher(str1);
		
		System.out.println(m.results().count());
		
		m.reset();
		
		while(m.find()) {
			System.out.println("Starts at:"+m.start());
			System.out.println(m.group());
		}
		
		
		
	}

}
