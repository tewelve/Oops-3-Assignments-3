# Oops-3-Assignments-3


public class Encapsulation 
{
	 private int ssn;
	    private String empName;
	    private int empAge;
		public int getSsn() {
			return ssn;
		}
		public void setSsn(int ssn) {
			this.ssn = ssn;
		}
		public String getEmpName() {
			return empName;
		}
		public void setEmpName(String empName) {
			this.empName = empName;
		}
		public int getEmpAge() {
			return empAge;
		}
		public void setEmpAge(int empAge) {
			this.empAge = empAge;
		}
	public static void main(String[] args) 
	{
	Encapsulation obj = new Encapsulation();
     obj.setEmpName("Matt");
     obj.setEmpAge(32);
     obj.setSsn(123456789);
    System.out.println("Employee Name: " + obj.getEmpName());
    System.out.println("Employee Ssn: " + obj.getSsn());
    System.out.println("Employee Age: " + obj.getEmpAge());
}
}
