package oops_concepts;

public class Static_Main {

	public static void main(String[] args) {
		
		Static_Keyword sk1 = new Static_Keyword();
		
		Static_Keyword sk2 = new Static_Keyword();
		
		sk1.age = 7;
		sk1.grade = "2nd";
		Static_Keyword.name = "Rob";
		Static_Keyword.doThis();
		
		sk2.age = 8;
		sk2.grade = "3rd";
		Static_Keyword.name = "Shyam";
		Static_Keyword.doThis();
		
		sk1.displayDetails();
		sk2.displayDetails();

	}

}
