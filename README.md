import java.util.Scanner;

public class ProgramelseIfladder 
{
	public static void main(String[] args) 
	{
		Scanner scan = new Scanner(System.in);
		System.out.println("Enter the marks");
		int marks = scan.nextInt();
			if (marks > 90 && marks <=100)
				{
				System.out.println("Grade--A");
				}
			else if (marks > 70 && marks <=90)
				{
				System.out.println("Grade--B");
				}   
			else if (marks > 50 && marks <=70)
				{
				System.out.println("Grade--C");
				}
			else if (marks >= 35 && marks <=50)
				{
				System.out.println("Grade--D");
				}
			else if (marks >= 0 && marks <35)
				{
				System.out.println("Fail");
				}
			else
				{
				System.out.println("Invalid marks");
				}
	}
}
