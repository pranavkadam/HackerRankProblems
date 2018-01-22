import java.io.*;
import java.util.*;
import java.text.*;
import java.math.*;
import java.util.regex.*;
import java.util.Stack; 


public class Solution {

    public static void main(String[] args) {
        Stack<Integer> stack = new Stack<Integer>();
        Scanner sc=new Scanner(System.in);
        int n=sc.nextInt();
        int x;
        for (int i = 0; i < n; i++){
            int q=sc.nextInt();
            
            switch(q){
                case 1:
                    x=sc.nextInt();
                    stack.push(x);
                    break;
                    
                case 2:
                    stack.pop();
                    break;
                    
                case 3:
                    Stack<Integer> reverseLifo = new Stack<Integer>();
                    int max = 0;
                    
                    if(stack.isEmpty()){
                        break;
                    }

                    while (!stack.isEmpty())
                    {
                    int val = stack.pop();

                    max = Math.max(val, max);

                    reverseLifo.push(val);
                    }

                    while (!reverseLifo.isEmpty())
                    {
                    stack.push(reverseLifo.pop());
                    }

                    System.out.println(max);
                    
                    
                    break;
                    
                default:
                    System.out.println("Wrong entry");
                    break;
                    
            }
            
            
        }
    }
}
