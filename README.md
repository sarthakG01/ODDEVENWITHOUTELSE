# ODDEVENWITHOUTELSE
We can find Odd even numbers without using else

public class evenoddwithoutelse {
	public static void main(String[]args) {
		Checkeven(5);
	}
	
public static void Checkeven(int num) {
	
	if ((num/2)+2==num) {
		System.out.println("Its Even Number");
		return;
	}
	System.out.println("Its odd number");

}
}

