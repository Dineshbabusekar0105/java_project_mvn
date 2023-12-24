# This is a simple java project -in this project you can calculate the length of the given words  
package com.example;

import java.util.Scanner;

public class App 
{
    public static void main( String[] args )
    {
	Scanner scanner = new Scanner(System.in);
        System.out.print( "enter the word:" );

	String word = scanner.nextLine();

	int length = word.length();

	System.out.println("length of the entered word is:"+length);

	scanner.close();
    }
}
