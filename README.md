# Area-of-a-circle
package javaprogramming;
import java.util.*;
public class Areacircle {
	public static void main(String[] args) {
		Scanner j=new Scanner(System.in);
		double PI=Math.PI;
		int radius;
		double Area;
		
		System.out.println("Enter the radius of the Circle : ");
		radius=j.nextInt();
		
		Area=PI*radius*radius;
		
		System.out.println("The Area of the Circle is : "+Area);

	}


}
