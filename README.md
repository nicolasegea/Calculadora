import javax.swing.JOptionPane;

public class Dollar  {
    public static void main (String[] args) {
        double primeirovalor, segundovalor, resultado;
        primeirovalor = Double.parseDouble(JOptionPane.showInputDialog("primeiro valor"));
        segundovalor = Double.parseDouble(JOptionPane.showInputDialog("segundo valor"));
    resultado = primeirovalor + segundovalor;
    JOptionPane.showMessageDialog(null, "soma = " + resultado);
}
    
}
