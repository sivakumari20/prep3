# prep3


package my_first_java_Project;
import java.util.Scanner;

public class main {

	public static void main(String[] args) {
	Scanner sc=new Scanner(System.in);
	System.out.println("enter no of rows");
	int rows=sc.nextInt();
	System.out.println("enter no of coloumns");
	int coloumns=sc.nextInt();
	for (int i=0;i<rows;i++) {
	  for(int j=0;j<coloumns;j++) {
		  System.out.print(i);
	  }
	 System.out.println();
	}
	}
}

enter no of rows
5
enter no of coloumns
5
00000
11111
22222
33333
44444


package my_first_java_Project;
import java.util.Scanner;

public class main {

	public static void main(String[] args) {
	Scanner sc=new Scanner(System.in);
	System.out.println("enter no of rows");
	int rows=sc.nextInt();
	System.out.println("enter no of coloumns");
	int coloumns=sc.nextInt();
	for (int i=1;i<rows;i++) {
	  for(int j=1;j<coloumns;j++) {
		  System.out.print(j);
	  }
	 System.out.println();
	}
	}
}

enter no of rows
5
enter no of coloumns
5
1234
1234
1234
1234

