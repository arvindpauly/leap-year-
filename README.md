# leap-year
import java.util.Scanner;
public class oddoreven {
	public static void main(String [] arg){
	Scanner ab=new Scanner(System.in);
	int x;
	System.out.println("enter the year to know whether is leap year or not ");
	x=ab.nextInt();
	if(x/4==0)
	{
		System.out.println("the given year "+x+"is leap year");
	}
	else
	{
		System.out.println(" the given year"+x+"is not a leap year");
		
	}

}
}
