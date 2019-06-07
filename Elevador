 Elevador

class Elevador {
private int andarAtual, andaresP, capacidadeE, qtdPessoas;
public Elevador( int andaresP, int capacidadeE){
this.andarAtual = 0;
this.andaresP = andaresP;
this.capacidadeE = capacidadeE;
this.qtdPessoas = 0;
}

public void entrar(){
if (capacidadeE > qtdPessoas){
qtdPessoas ++;
}
}

public void Sair(){
if(qtdPessoas > 0){
qtdPessoas --;
}
}

public void Subir(int andarDesejado){
if(andarAtual != andaresP && andarDesejado <= andaresP && andarDesejado > andarAtual){
andarAtual = andarDesejado;
}
}

public void Descer(int andarDesejado){
if(andarAtual != 0 && andarDesejado < andarAtual && andarDesejado >= 0){
andarAtual = andarDesejado;
}
}

public int getandarAtual(){
return andarAtual;
}

public void setandarAtual(int andarAtual){
this.andarAtual = andarAtual;
}

public int getandaresP(){
return andaresP;
}

public void getandaresP(int andaresP){
this.andaresP = andaresP;
}

public int getcapacidadeE(){
return capacidadeE;
}

public void setcapacidade_E(int capacidadeE){
this.capacidadeE = capacidadeE;
}

public int getqtdPessoas(){
return qtdPessoas;
}

public void setqtdPessoas(int qtdPessoas){
this.qtdPessoas = qtdPessoas;
}

}
public class Main {
public static void main(String[] args) {
Elevador e = new Elevador (15, 7);
System.out.println("Andar Atual: " + e.getandarAtual());
e.entrar();
System.out.println("Andar Atual: " + e.getandarAtual());
System.out.println("Total de Andares: " + e.getandaresP());
System.out.println("capacidade: " + e.getcapacidadeE());
System.out.println("Quantidade de Pessoas: " + e.getqtdPessoas());
e.Subir(5);
e.Descer(2);
e.Sair();
System.out.println("Andar Atual: " + e.getandarAtual());
System.out.println("Quantidade de Pessoas: " + e.getqtdPessoas());

e.entrar();
e.entrar();
e.entrar();
e.entrar();
e.entrar();
e.entrar();
e.entrar();
e.entrar();
e.entrar();

System.out.println("Quantidade de Pessoas: " + e.getqtdPessoas());

e.Subir(10);
System.out.println("Andar Atual: " + e.getandarAtual());
}
}
