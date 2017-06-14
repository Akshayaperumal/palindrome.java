# palindrome.java
import java.io.*;
import java.util.*;
class palindrome
{
    public static void main(String args[])
    {
        Scanner s=new Scanner(System.in);
        int a=s.nextInt();
        int b=0;
        if(a!=0)
        {
            int r=a%10;
            b=b*10+r;
            a=a/10;
        }
        if(a==b)
        {
            System.out.println("true") ;
        }
        System.out.println("false");
        
    }
}
