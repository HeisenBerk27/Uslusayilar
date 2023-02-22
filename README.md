# Uslusayilar
www.patika.dev
--------------


import java.util.Scanner;

public class ÜsFor 
{

	public static void main(String[] args) 
	{
		
		Scanner scanner = new Scanner(System.in);
		
		int toplam= 1;
		System.out.println("Us alınacak sayiyi giriniz: ");
		int ust = scanner.nextInt();
		System.out.println("kuvvet sayisini giriniz: ");
		int kuvvet = scanner.nextInt();
		
		for(int i =1; i<=kuvvet; i++)
		{
			toplam = toplam * ust;	
		}
		
		System.out.println(toplam);
	}

}
