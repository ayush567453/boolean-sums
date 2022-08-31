# boolean-sums
/******************************************************************************

Welcome to GDB Online.
GDB online is an online compiler and debugger tool for C, C++, Python, Java, PHP, Ruby, Perl,
C#, OCaml, VB, Swift, Pascal, Fortran, Haskell, Objective-C, Assembly, HTML, CSS, JS, SQLite, Prolog.
Code, Compile, Run and Debug online from anywhere in world.

*******************************************************************************/
import java.util.*;
public class Main
{
	public static void main(String[] args) {
	Scanner sc=new Scanner(System.in);
	int m=sc.nextInt();
	int n=sc.nextInt();
	int [][]mat=new int[m][n];
	for(int i=0;i<m;i++){
	    for(int j=0;j<n;j++){
	        mat[i][j]=sc.nextInt();
	    }
	}
	int flag=0;
	for(int i=0;i<m;i++){
	    flag=0;
	    for(int j=0;j<n;j++){
	        if(mat[i][j]==1){
	            flag=1;
	        }
	    }
	    for(int j=0;j<n;j++){
	        System.out.print(flag+" ");
	    }
	    System.out.println();
	}
	}
}
