# Trabalho-de-SO

import java.util.Scanner;
import java.util.Random;

public class Main {
	Scanner sc = new Scanner(System.in);
	static int  buffer;//(RC)tempo de cada thread
	static int c;//numero de canais da tv
	static int n;//numero de hospedes
	
	
	
	
	public static class Hospede extends Thread{//hóspede
		n = nexInt();
		public  void run() {
			System.out.println("ai");
		}
	}
	
	public static void main(String[] args) {
		
	}
}
