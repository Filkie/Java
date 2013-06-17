public class MathClass {

  public static void main(String[] args) {
		int number1;
		int number2;
		int result;

		number1 = 22;
		number2 = 3;
		result = number1 + number2;
		System.out.println(number1 + " + " + number2 + " = " + result);

		number1 = result;
		number2 = result - 2;
		result = number1 * number2;
		System.out.println(number1 + " * " + number2 + " = " + result);
	
	final float PI = 3.14159265359f;
	
	float radius;
	float circumference;
	
	radius = PI;
	
	circumference = 2 * radius * PI;
	
	System.out.println("PI = " + PI);
	System.out.println("circumference = " + circumference);

	}

}
