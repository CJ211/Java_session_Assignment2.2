# Java_session_Assignment2.2
//X pattern

import java.util.*;

class xpattern
{
	public static void main(String args[])
	{
		Scanner sc=new Scanner(System.in);
		System.out.println("Enter the no of lines the");
		int n=sc.nextInt();
		int i,j;

		for(i=0;i<n;i++)
		{
			for(j=0;j<n;j++)
			{
				if(j==i)
				{
					System.out.print("*");
				}
				else if(j==(n-i-1))
				{
					System.out.print("*");	
				}
				
				else
				{ 
					System.out.print("_");
				}
			}
			System.out.println();			
		}		
	}
}
