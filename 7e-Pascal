import java.util.Scanner;
public class Strings
{
    public static void main(String[] args)
    {
        Scanner s=new Scanner(System.in);
        System.out.print("enter");
        int a=s.nextInt();
        int value=1;
        for(int i=1;i<=a;i++)
        {
            for(int j=0;j<=a-i;j++)
            {
                System.out.print(" ");
            }
            for(int k=1;k<=i;k++)
            {
                System.out.print(value+" ");
                value=value*(i-k)/k+1;
            }
            System.out.println();
            s.close();
        }
    }
}
