# part1-practical2
package part1;
import java.util.Scanner;

 public class Practical2 {
	 public static void main(String[] args) {
	        try (Scanner a = new Scanner(System.in)) {
				for(int i=0;i<3;i++) {
				    String s=a.nextLine();
				    char ch=s.charAt(0);
				    char c=s.charAt(1);

				    if (ch == 'o' && c == 'z') {
				        System.out.print(ch);
				        System.out.println(c);
				    } else if (c == 'z') {
				        System.out.println(c);
				    } else if (ch =='o'){
				        System.out.print(ch);
				    }
				    else{
				        System.out.print(ch);
				        System.out.println(c);
				    }
				}
			}
	System.out.print("21CE063_Manav.");
	    }
	

}

