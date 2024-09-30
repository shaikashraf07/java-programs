import java.util.*;
class expression{
    public static void main(String[]args){
        System.out.println("FINDING THE VALUE ");
        Scanner sc=new Scanner(System.in);
        System.out.println("enter the final velocity");
        double v=sc.nextDouble();
        System.out.println("enter the itial velocity");
        double u=sc.nextDouble();
        System.out.println("enter the acceleration");
        double a=sc.nextDouble();
         System.out.println("enter the speed");
        double s=sc.nextDouble();
        
        double result=(Math.pow(v,2) - Math.pow(u,2))/(2*a*s);
        System.out.println(result);
    }
}
