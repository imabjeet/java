import java.io.*;

public class diamond
{
	public static void main(String args[])
	{
		for(int i=0;i<=2;i++)
		{
			for(int j=0;j<=2-i;j++)
			{
				System.out.print(" ");
			}
			for(int j=0;j<=i;j++)	
			{
				System.out.print("* ");
			}
			System.out.println("");
		}
		
		for(int i=0;i<=1;i++)
		{
			for(int j=1-i;j<=1;j++)
			{
				System.out.print(" ");
			}
			for(int j=i;j<=1;j++)	
			{
				System.out.print(" *");
			}
			System.out.println("");
		}

	}
}
