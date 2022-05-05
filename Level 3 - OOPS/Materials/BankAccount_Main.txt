package oops_concepts;

public class BankAccount_Main {

	public static void main(String[] args) {
		
		Bank_Account b1 = new Bank_Account(123456,"De ZINNIA",100000);
		
		b1.displayCurrentBalance();
		
		b1.withdraw(2000);
		
		b1.displayCurrentBalance();
		
		b1.deposit(-1000);
		
		b1.displayCurrentBalance();
		
		b1.deposit(20000);
		
		b1.displayCurrentBalance();
		
	}

}
