MAIN - package br.una.psc.cli;

import br.una.psc.cli.Exercicios.Exercicios01;

import java.util.Scanner;

public class Main {
    public static void main (String[] args) {
        Scanner input = new Scanner(System.in);
        Exercicios01 exercicios01 = new Exercicios01(input);

        exercicio01.executar();

    }
}

package Exercicios;

import java.util.Scanner;

public class Exercicios01 {
    Scanner entrada; 1

    public Exercicios01(Scanner entrada) {
        this.entrada = entrada;
    }
}
 public void executar() {
     // Escrever a Lógica do exercicio 01
     double numeroBase;
     double resultado;

     System.out.print ("informe um número:");
     numeroBase = entrada.nextDouble();
     System.out.prinln(); // linha branca

     resultado = numeroBase * 2; // Calculo do dobro
     System.out.printl("a dobra de" + numeroBase + "é" + resultado);

 }
