Java
====
package uygulama;
import java.util.Scanner;

public class uygula {

	public static void main(String[] args) 
	{
		Scanner input=new Scanner(System.in);
		
		int[] dizi1={4,5,7,9,6};
		int[] dizi2={5,87,25,69,58};
		diziTopla(dizi1, dizi2);
		
	}
	public static void diziTopla(int x[], int y[])
	{
		int i;
		int a[]=new int[5];
		for(i=0;i<5;i++)
		{
			a[i]=x[i]+y[i];
			System.out.println(i+1+".eleman:"+a[i]);
		}
		
		
	}

}
