package oops_concepts;

public class Employee {
	
	/**
	 * ****Class Example****
	 * 1. Create an Employee Class
	 * 2. Create class variables for Employee Name, Employee ID, Employee Salary 
	 * 3. Create a method to calculate and display Employee bonus (20% of Employee Salary)
	 * 4. Create an Employee_Main class with a Main Method
	 * 5. Create 2 Objects of Employee Class in Employee_Main
	 * 6. Assign values to variables and call the method from Employee Class by using the objects created in step 5
	 */
	
	String empName = "ABC";
	int empId = 100;
	int empSalary = 1000;
	
	public void displayEmployeebonus() {
		System.out.println("Employee " + empName + " gets the bonus of " + (empSalary * 0.20) );
	}

}
