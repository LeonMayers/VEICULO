// Classe que representa um Carro
public class Carro {
    // Propriedades do carro
    private String marca;
    private String modelo;
    private int ano;

    // Construtor para inicializar um novo carro
    public Carro(String marca, String modelo, int ano) {
        this.marca = marca;
        this.modelo = modelo;
        this.ano = ano;
    }

    // Método para obter a marca do carro
    public String getMarca() {
        return marca;
    }

    // Método para definir a marca do carro
    public void setMarca(String marca) {
        this.marca = marca;
    }

    // Método para obter o modelo do carro
    public String getModelo() {
        return modelo;
    }

    // Método para definir o modelo do carro
    public void setModelo(String modelo) {
        this.modelo = modelo;
    }

    // Método para obter o ano do carro
    public int getAno() {
        return ano;
    }

    // Método para definir o ano do carro
    public void setAno(int ano) {
        this.ano = ano;
    }

    // Método para exibir as informações do carro
    public void exibirInformacoes() {
        System.out.println("Marca: " + marca + ", Modelo: " + modelo + ", Ano: " + ano);
    }

    // Método principal para testar a classe Carro
    public static void main(String[] args) {
        // Criação de um objeto Carro
        Carro meuCarro = new Carro("Toyota", "Corolla", 2021);

        // Exibindo as informações do carro
        meuCarro.exibirInformacoes();

        // Alterando algumas propriedades do carro
        meuCarro.setMarca("Honda");
        meuCarro.setModelo("Civic");
        meuCarro.setAno(2022);

        // Exibindo as informações atualizadas do carro
        meuCarro.exibirInformacoes();
    }
}

