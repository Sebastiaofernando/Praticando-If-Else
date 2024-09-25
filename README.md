# Praticando-If-Else
Neste repositório o principal ovjetivo foi praticar alguns conceitos de if &amp; Else, para recapitular alguns conceitos já estudado anteriormente.

Alguns exercícios : 

1 :  Escreva um programa que receba o raio de uma circunferência e mostre o diâmetro, comprimento e área desta.

package JavaBasico;
import java.util.Scanner;

public class Exercicios {
	
	public static void main (String []args) {
		
		//  Escreva um programa que receba o raio de uma circunferência e mostre o diâmetro, comprimento e área desta.
		
		Scanner sc = new Scanner(System.in);
		
		double raio;
		double diametro = 0;
		double comprimento = 0;
		double area = 0;
		
		System.out.println("Qual é o valor do raio da circunferencia? ");
		raio = sc.nextDouble();
		
		diametro = 2 * raio;
		
		System.out.println("Neste caso, o valor do diametro de acordo ao valor do raio digitado será de: " + diametro);
		
		comprimento = 2 * 3.14 * raio;
		
		System.out.println("Neste caso, o valor do comprimento de acordo ao valor do raio digitado será de: " + comprimento);
		
		area = 3.14 * raio * raio;
		
		System.out.println("Neste caso, o valor da area de acordo ao valor do raio digitado será de: " + area);
		
		sc.close();
	}

}


