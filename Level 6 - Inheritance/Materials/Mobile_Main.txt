package abstraction;

public class Mobile_Main {

	public static void main(String[] args) {
		
		Mobile m;
		
		m = new IOS();
		m.doubleTap();
		
		m = new Android();
		m.doubleTap();

	}

}
