# MiniProyectos
package listasuper;

/**
 *
 * @author Alejandro
 */
public class ListaSuper {

    /**
     * @param args the command line arguments
     */
    public static void main(String[] args)  {
        // TODO code application logic here
        double precio;
      
        Alimentos.yerba.precio=50;
        Alimentos.arroz.precio=20;
        
        System.out.println("Precio de la yerba: " + Alimentos.yerba.precio);
        System.out.println("Precio del arroz: " + Alimentos.arroz.precio);
        
        double total = (Alimentos.yerba.precio+Alimentos.arroz.precio);
        
        System.out.println("El total es: " + total);
        
    
    }
    
}
public enum Alimentos {
 yerba,azucar,cafe,arroz,fideos;
 double precio;


    public static Alimentos getYerba() {
        return yerba;
    }

    public static Alimentos getAzucar() {
        return azucar;
    }

    public static Alimentos getCafe() {
        return cafe;
    }

    public static Alimentos getArroz() {
        return arroz;
    }

    public static Alimentos getFideos() {
        return fideos;
    }
    
}
