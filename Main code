import java.util.*;
public class Hwww
{
        public static void main(String[] args) {
                int n,n1;
                Scanner s=new Scanner(System.in);
                System.out.print("Enter list1: ");
                n=s.nextInt();
                int a[]=new int[n];
                for(int i=0;i<n;i++){
                    a[i]=s.nextInt();
                }
                System.out.print("Enter list2: ");
                n1=s.nextInt();
                int b[]=new int[n1];
                for(int i=0;i<n1;i++){
                    b[i]=s.nextInt();
                }
                ArrayList<Integer> al=new ArrayList<Integer>();
                for(int i=0;i<n;i++){
                        for(int j=0;j<n1;j++){
                        if(a[i]==b[j]){
                            al.add(a[i]);
                        }
                    }
                }
                System.out.print("The common elements are ");
                for(int i:al){
                    System.out.print(i+" ");
                }
        }
}
