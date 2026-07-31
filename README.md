[veiculo.java](https://github.com/user-attachments/files/30568526/veiculo.java)
import static java.lang.IO.*;

public class veiculo {
    public String cor;
    public String marca;
    public String modelo;

    public String acelerar(){
        return "Vruuuuummmmm";
    }

    public String freiar(){
        return "iriiiiiiiii";
    }

    public veiculo(String cor, String marca, String modelo) {
        this.cor = cor;
        this.marca = marca;
        this.modelo = modelo;
    }

    @Override
    public String toString() {
        return "veiculo{" +
                "cor='" + cor + '\'' +
                ", marca='" + marca + '\'' +
                ", modelo='" + modelo + '\'' +
                '}';
    }
}
