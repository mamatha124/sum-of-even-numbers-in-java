# sum-of-even-numbers-in-java
import java.util.*;
class Main{
    public static void main(String[] args){
        Scanner sc=new Scanner(System.in);
        int n=sc.nextInt();
        int sum=0;
        int k=1;
        while(k<=n){
            if(k%2==0){
                sum=sum+k;
            }
            k++;
        }
         System.out.println(sum);
    }
}
    
