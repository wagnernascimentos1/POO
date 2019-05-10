class Funcionario {
    private int codigo;
    private String nome;
    private String cpf;
    private String endereço;
    private String telefone;
    private int idade;
    private float salario;
    private int ndependentes;
   
   
    public Funcionario (int codigo, String nome, String cpf, String endereço, String telefone, int idade, float salário, int ndependentes) {
        this.codigo = codigo;
        this.nome = nome;
        this.cpf = cpf;
        this.endereço = endereço;
        this.telefone = telefone;
        this.idade = idade;
        this.salario = salario;
        this.ndependentes = ndependentes;
    }
   
    public int getCodigo(){
        return codigo;
    }
    public void setCodigo (int codigo){
        this.codigo = codigo;
    }
    public String getNome(){
        return nome;
    }
    public void setNome (String nome){
        this.nome = nome;
    }
    public String getCpf(){
        return cpf;
    }
    public void setCpf (String cpf){
        this.cpf = cpf;
    }
    public String getEndereço(){
        return endereço;
    }
    public void setEndereço(String endereço){
        this.endereço = endereço;
    }
    public String getTelefone(){
        return telefone;
    }
    public void setTelefone (String telefone){
        this.telefone = telefone;
    }
    public int getIdade(){
        return idade;
    }
    public void setIdade (int idade){
        this.idade = idade;
    }
    public float getSalario(){
        return salario;
    }
    public void setSalario (float salario){
        this.salario = salario;
    }
    public int getNdependentes(){
        return ndependentes;
    }
    public void setNdependentes (int ndependentes){
        this.ndependentes = ndependentes;
    }
   
   
    public float calculaSalarioLiquido (int percent){
       
        return salario - salario * 0.11f + (ndependentes * salario * percent/100);
    }

}
    public class Main{


    public static void main (String [] args){
        Funcionario f = new Funcionario(01, "Wagner", "12898005452", "Rua Castelo Branco", "4002-8922", 17, 1.500f, 2);
     System.out.println (f.getCodigo());
    System.out.println (f.getNome());
    System.out.println (f.getCpf());
    System.out.println (f.getEndereço());
    System.out.println (f.getTelefone());
    System.out.println (f.getIdade());
    System.out.println (f.getSalario());
    System.out.println (f.getNdependentes());
} 
       
   
}
