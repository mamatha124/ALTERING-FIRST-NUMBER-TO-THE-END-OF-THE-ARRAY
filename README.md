# ALTERING-FIRST-NUMBER-TO-THE-END-OF-THE-ARRAY
import java.util.*;
class HelloWorld {
    public static void main(String[] args) {
       Scanner sc=new Scanner(System.in);
        int l=sc.nextInt();
        int n[]=new int[l+1];
        int j=0;
        System.out.print("Enter array: ");
        for(int i=0;i<l;i++){
            int k=sc.nextInt();
            n[i]=k;
        }
        n[l]=n[0];
        n[0]=0;
        System.out.print("Array after altering: ");
        for(int i=1;i<=l;i++){
            System.out.print(n[i]+" ");
        }
    }
}
