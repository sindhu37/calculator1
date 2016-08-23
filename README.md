# calculator1
package com.task;

import java.util.Scanner;

public class Calculator {
	//static int a;
	//static int b;
	//static int z;
	
	public static void main(String[] args) {
		// TODO Auto-generated method stub
        try{
		Scanner obj=new Scanner(System.in);
        System.out.println("Enter two numbers ");
      //  System.out.print();
        int a=obj.nextInt(); 
      //  System.out.print("Enter b value = ");
        int b=obj.nextInt();
        System.out.print("Enter choice ");
        int c ;char d;
        
  do{
		System.out.println("1.Add 2.Sub 3.Mul 4.Div");
		int z=obj.nextInt();

		
switch(z)
	    {
        case 1:
        	c=a+b;
        	System.out.println("Addition Value "+c);
        	break;
case 2:
        	c=a-b;
        	System.out.println("Subtraction Value "+c);
        	break;
        case 3:
        	c=a*b;
        	System.out.println("Multiplication Value "+c);
        	break;
        case 4:
        	float f=a/b;
        	System.out.println("Division Value "+f);
        	break;
        default :
        	System.out.println("Please enter any choice");  
        	continue;
        	
}
System.out.println("Do you want to continute?-If yes press 'y' or 'Y'");
d=obj.next().charAt(0);
if(d=='y'||d=='Y')
{
	continue;
}
else
{
	break;
}
    }while(true);
        }
        catch(Exception e)
        {
        	System.out.println("Exception Occur-Invalid Data type");
        }
		
        }
        }

        

   
	   
        
        


