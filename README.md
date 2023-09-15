# SayininUssu

package us;

import java.util.Scanner;

public class main {

	public static void main(String[] args) {
	
		int n,k,c = 1;

		Scanner input = new Scanner(System.in);
		
		System.out.println("Ussu alinacak sayiyi girin:");
		n = input.nextInt();

		System.out.println("Bu sayinin hangi ussu alinacak: ");
		k = input.nextInt();
		
		for (int i=1; i<=k; i++) {
	   c *= n;
		}
		
		System.out.println("Cevap:" +c);

      }
}
