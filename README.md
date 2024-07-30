# Vowels
import java.io.BufferedReader;
import java.io.IOException;
import java.io.InputStreamReader;
import java.util.Scanner;

public class Main
{
    public static void main(String[] args) throws Exception
    {
         char n;
         BufferedReader bf = new BufferedReader(new InputStreamReader(System.in));
         System.out.println("enter the character you want:");
         n=(char)bf.read();
         switch(n)
         {
            case 'a':
                System.out.println("the given character "+n+" is vowel");
                break;
            case 'e':
                System.out.println("the given character "+n+"is vowel");
                break;
            case 'i':
                System.out.println("the given charcater "+n+"is vowel");
                break;
            case 'o':
               System.out.println("the given charcater "+n+"is vowel");
               break;
            case 'u':
                System.out.println("the given charcater "+n+"is vowel");
                break;
            default:
                System.out.println("the given character "+n+" consonent");
                break;
                
        }
    }
}
