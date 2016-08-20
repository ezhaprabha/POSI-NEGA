# POSI-NEGA
import java.util.Scanner;
public class Postive_Negative 
{
public static void main(String[] args) 
{
Integer r;
Scanner s = new Scanner(System.in);
System.out.print("Enter the number:");
r = s.nextInt();
if(r > 0)
{
System.out.println("The given number "+r+" is Positive");
}
else if(r < 0)
{
System.out.println("The given number "+r+" is Negative");
}
else
{
System.out.println("The given number "+r+" is neither Positive nor Negative ");
}
}
}
