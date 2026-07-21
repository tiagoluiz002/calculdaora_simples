import java.util.Scanner;

public class main {

    public static void main(String[] args) {

        Scanner scanner = new Scanner(System.in);

        System.out.println("Digite seu primeiro numero: ");
        double num1 = scanner.nextDouble();

        System.out.println("Digite seu segundo numero: ");
        double num2 = scanner.nextDouble();

        System.out.println("Digite a operacao: ");
        String operacao = scanner.next();

        double resultado = 0;

        if (operacao.equals("+")) {
            resultado = num1 + num2;
        } else if (operacao.equals("-")) {
            resultado = num1 - num2;
        } else if (operacao.equals("*")) {
            resultado = num1 * num2;
        } else if (operacao.equals("/")) {
            resultado = num1 / num2;
        } else {
            System.out.println("Erro! Divisao por zero!");
            return;
        }

        System.out.println("Resultado: " + resultado);
    }

}

