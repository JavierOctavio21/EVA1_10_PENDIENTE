import java.util.*;

/**
 *
 * @author Javier Octavio
 */
public class Principal {

    /**
     * @param args the command line arguments
     */
    public static void main(String[] args) {
        // TODO code application logic here
        Scanner input = new Scanner(System.in);
        System.out.println("Introduce la Ubicación del Punto A");
        double rX1;
        
        rX1 = input.nextDouble();
        double rY1;
        
        rY1 = input.nextDouble();
        System.out.println("Introduce la Ubicación del Punto B");
        double rX2;
        
        rX2 = input.nextDouble();
        double rY2;
        
        rY2 = input.nextDouble();
        double rFormula;
        
        rFormula = (rY2 - rY1) / (rX2 - rX1);
        System.out.print("La Pendiente de la Recta es: ");
        System.out.println(rFormula);
    }
}
