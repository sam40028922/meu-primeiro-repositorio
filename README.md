import java.util.Scanner;

public class PrimeiroPrograma {

    public static void main(String[] args){

        Scanner scanner = new Scanner(System.in);

        System.out.println("olá seja bem vindo, digite o seu nome:");
        String nome = scanner.nextLine();

        System.out.println("agora digite a sua idade:");
        int idade = scanner.nextInt();

        System.out.println("agora digite sua altura:");
        double altura = scanner.nextDouble();


        scanner.close();

        System.out.println("O seu nome é " + nome + ", voce tem " + idade + " anos, e sua altura é " + altura);


    }
}
