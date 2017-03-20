# NumeroConsecutivo
Ler o próximo número

public class NumeroConsecutivo {
    public static void main(String[] args) {
    //criando o scanner
    Scanner leitor = new Scanner (System.in);
      //declaração de variáveis
     int n1, n2, pn1, pn2;
        System.out.print("Digite o primeiro número: ");
        n1 = leitor.nextInt();
        System.out.print("Digite o segundo número: ");
        n2 = leitor.nextInt();
     pn1 = n1+1;
        System.out.println("O número consecutivo ao primeiro número digitado é: " + pn1);
  }
}
