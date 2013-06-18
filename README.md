import java.util.Scanner;

public class MathClass {

	public static void main(String[] args) {
		int number1;
		int number2;
		int result;
		float answer;
		int selectedRadius;
		final float PI = 3.14159265359f;
		number1 = 22;
		number2 = 3;
		result = number1 + number2;
		Scanner one = new Scanner(System.in);
		System.out.println("Hello, what is your desired radius?");
		selectedRadius = one.nextInt();
		answer = selectedRadius * PI;

		float radius;
		float circumference;

		radius = PI;

		circumference = 2 * radius * PI;

		System.out.println("PI = " + PI);
		System.out.println("Answer: " + selectedRadius * PI);

	}

}
