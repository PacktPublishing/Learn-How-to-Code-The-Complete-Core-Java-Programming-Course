package sets;

import java.util.LinkedHashSet;

public class Linked_Hash_Set {

	public static void main(String[] args) {
		
		/*
		 * A LinkedHashSet is an ordered version of HashSet 
		 * LinkedHashSet maintains a doubly-linked List across all elements
		 * No positional access of elements
		 * Basic Methods: add, remove, clear, contains, size, 
		 * IMP: Union and Intersection of Sets
		 * IMP: Convert set to list
		 */
		
		LinkedHashSet<Character> set1 = new LinkedHashSet<Character>();
		
		set1.add('a');
		set1.add('e');
		set1.add('i');
		set1.add('o');
		set1.add('u');
		
		System.out.println(set1);
		
		
	}

}
