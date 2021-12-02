import java.util.Scanner;

public class CodesCracker
{
   public static void main(String[] args)
   {
      String str;
      char ch, strCh;
      int strLen, i, count=0;
      Scanner s = new Scanner(System.in);
      
      System.out.print("Enter the String: ");
      str = s.nextLine();
      System.out.print("\nEnter a Character to Find its Frequency: ");
      ch = s.next().charAt(0);
      
      strLen = str.length();
      for(i=0; i<strLen; i++)
      {
         strCh = str.charAt(i);
         if(ch==strCh)
            count++;
      }
      
      System.out.println("\nFrequency = " +count);
   }
}
