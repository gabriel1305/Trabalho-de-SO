# Trabalho-de-SO

import java.util.Scanner;

public class Main {

	public static void main(String[] args) {
		Scanner sc = new Scanner(System.in);
		int n;
		int c;
		int restmin;
		int restmax;
		int watchmin;
		int watchmax;
		
		System.out.println("Digite a quantidade de hospedes:");
		n = sc.nextInt();//lendo o numero de hospedes
		
		System.out.println("Digite a quantidade de canais da Tv");
		c = sc.nextInt();//lendo o numero de canais
		
		System.out.println("Digite o tempo minimo de descanso");
		restmin = sc.nextInt();//minimo do intervalo de descanso
		
		System.out.println("Digite o tempo maximo de descanso");
		restmax = sc.nextInt();//maximo do intervalo de descanso
		
		System.out.println("Digite o tempo minimo de ver tv");
		watchmin = sc.nextInt();//minimo do intervalo de ver tv
		
		System.out.println("Digite o tempo maximo de ver tv");
		watchmax = sc.nextInt();//maximo do intervalo de ver tv
		
		for(int i=0;i<n;i++) {
			Minha_Thread thread = new Minha_Thread(c);
			thread.start();
		}

	}
}
