# problem-13--A2.doc-


package problem.pkg13;

import java.util.Scanner;

public class Problem13 {

    public static void main(String[] args) {
        
        int i,j,star;
        Scanner input=new Scanner(System.in);
        System.out.println("enter the number");
        star=input.nextInt();
        for(i=1;i<=4;i++)
        {
             for(j=1;j<=6;j++)
            {
                System.out.print(" "+j);
            }
             
              System.out.println(" ");
        }
    }
    
}
