# Name: Maria Jolina Abella
Section: Devotion 
Year: 4th

import java.util.Scanner;
public class Main {
	public static void main(String[] args) {
		Scanner code=new Scanner(System.in);
		int i=;
		int total=;
		int rep=;
		
		while(i==){
		    System.out.println("ENTER GRADE:");
		    int grade=code.nextInt();
		    
		    total+=grade;
		    rep+=i;
		    
		    System.out.println("DO YOU WANT TO ENTER ANOTHER GRADE?\n[1]YES   [2]NO:");
		    i=code.nextInt();
		    
		}
		total=total/rep;
		System.out.println("AVERAGE:"+total);
    }	
}
