import java.util.*;
class gradecalc
{
    public static void main(String args[])
    {
        Scanner sc=new Scanner(System.in);
        int marks[]=new int[3];
        int i,total=0;
        float avg;
        for(i=0;i<3;i++)
        {
            System.out.println("ENTER MARKS OF YOUR SUBJECT"+(i+1));
            marks[i]=sc.nextInt();
            total=total+marks[i];
        }
        avg = total/3;
        System.out.print("YOUR GRADE IS : ");
        if(avg>=80)
        {
            System.out.print("A");
        }
        else if(avg>=60 && avg<80)
        {
           System.out.print("B");
        } 
        else if(avg>=40 && avg<60)
        {
            System.out.print("C");
        }
        else
        {
            System.out.print("D");
        }
    }
}
