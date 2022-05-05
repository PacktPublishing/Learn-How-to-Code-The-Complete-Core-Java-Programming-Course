package lists;

import java.util.LinkedList;
import java.util.ListIterator;

public class List_Iterator_Program2 {

	public static void main(String[] args) {
		
		/*
		 * Update all ODD numbers from a LinkedList to EVEN Numbers
		 */
		
		var list = new LinkedList<Integer>();
		
		list.add(10);
		list.add(20);
		list.add(11);
		list.add(23);
		list.add(100);
		list.add(30);
		list.add(111);
		list.add(119);
		
		ListIterator itr = list.listIterator();
		
		while(itr.hasNext()) {
			
			int i = (int) itr.next();
			if (i % 2 == 1) {
				i++;
				itr.set(i);
			}
			
		}
		
		System.out.println(list);
	}
}
