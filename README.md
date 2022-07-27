import java.io.*;
import java.util.*;

public class Solution {

    public static void main(String[] args) {
        /* Enter your code here. Read input from STDIN. Print output to STDOUT. Your class should be named Solution. */
        Scanner s=new Scanner(System.in);
        int N=s.nextInt();
        for(int num=0;num<=N;num++)
            if(num%7==0)
                System.out.print(num+" ");
    }
}
